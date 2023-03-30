# Machine_Learning_Naive_Bayes_classifier
# Data preprocessing, Build a Naive Bayes classifier and Make the classifier robust to missing data with Laplace (additive) smoothing.

# INTRODUCTION:
Naive Bayes is an algorithm for classification based on Bayes’ Theorem with an assumption of independence
among predictors. This is a MATLAB implementation of its behaviour. Laplace smoothing is applied. In statistics,
classification is the problem of identifying the category of an observation, based on a training set of data with
observations already classified. The classifiers implement a classification algorithm, that maps input data to a
category y.

# Naive Bayes Classifier

A Naive Bayes classifier is a probabilistic machine learning model that’s used for classification task. The classifier
is based on the Bayes theorem:
H is the hypothesis
X is the experimental observation
P(H) is the a priori probability of hypothesis H P(X) is the marginal probability of X
P(X—H) is the likelihood of observing X when H is verified.

![Picture1](https://user-images.githubusercontent.com/104999107/228851416-c6692d33-32a4-4eaf-b3ce-d9dbcd141d8d.png)

# Results
The error rate appears to float between 0.5 and 1, reaching the minor value of 0. The error rate is demonstrated
to be acceptable, confirming the efficiency of this kind of classification, even if is not that effective with a small set
of data. Thanks to the smoothing algorithm the results are improved.
