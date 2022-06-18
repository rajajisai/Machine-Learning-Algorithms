# machine-learning-algorithms
Implementation of basic machine learning algorithms form scratch

Major Libraries - numpy, pandas , matplotlib

-Fisher Discriminant

- -The Fisher Linear Discriminant Analysis method searches the data set given for directions having the largest inverse sum of variance and then projects the data into it thereby obtaining a lower dimensional form of the data set.
- -We assume that the projected points follow a normal distribution. We obtain the distributions for either class. Our threshold becomes the intersection of these two distributions which helps us to classify.
- -For 1D discriminant it is the intersection point of the reduced clusters, we classify the test point either greater and lesser than this threshold and for 3D w is the normal to the plane dividing the positive and negative examples.
-
-Linear Perceptron

The perceptron classifier is a well known classification especially when the data is linearly separable.
We start with a seed and try to get the optimal solution ( Hyperplane separating the positive and negative) using Stochastic Gradient Descent
We start iterating over all the data points all over again till we reach the terminating condition i.e. either there are no misclassified data points or we exceed the number of iterations.
Naive Bayes

The Naive Bayes is a generative model classifier. Here we have a binary classification problem of spam detection
7-fold cross validation is done on given dataset for Spam detection.
The Laplace smoothing is done by using the prior probability value as (1)/(n + |Vocabulary|).
