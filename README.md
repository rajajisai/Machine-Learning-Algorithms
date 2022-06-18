# machine-learning-algorithms
Implementation of basic machine learning algorithms form scratch

Major Libraries used are numpy, pandas , matplotlib

-Fisher Discriminant

- -The Fisher Linear Discriminant Analysis method searches the data set given for directions having the largest inverse sum of variance and then projects the data into it thereby obtaining a lower dimensional form of the data set.
- -We assume that the projected points follow a normal distribution. We obtain the distributions for either class. Our threshold becomes the intersection of these two distributions which helps us to classify.
- -For 1D discriminant it is the intersection point of the reduced clusters, we classify the test point either greater and lesser than this threshold and for 3D w is the normal to the plane dividing the positive and negative examples.
- - The yellow plane shown in the first image of the notebook is the discriminant.

-Linear Perceptron

- -The perceptron classifier is a well known classification especially when the data is linearly separable.We start with a seed vector and try to get the separating vector i.e the plane separating positive and negative points using Stochastic Gradient Descent
- -The terminating condition is that in the process of finding optimal solution,there are no misclassified points or we have reached maximum number of iteration

-Naive Bayes

- -The Naive Bayes is a generative model classifier.
- -We have used this classifier in the context spam detection
- -7-fold cross validation is done on given dataset for Spam detection.
- -The Laplace smoothing is done by using the prior probability value as (1)/(n + |Vocabulary|).
