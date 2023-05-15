# Naive-Bayes-Implementation

This repository contains an implementation of the Naive Bayes classifier. The Naive Bayes classifier is based on Bayes' theorem and assumes independence among features, making it efficient and effective for a wide range of applications.

## Features:
- **Fit**: The implementation includes a fit method to train the Naive Bayes classifier on a given training dataset, which learns the class probabilities and conditional probabilities of the features.
- **Predict**: The predict method can be used to make predictions on new data, leveraging the learned probabilities to determine the most likely class label for each instance.
- **Laplace Smoothing**: The classifier incorporates Laplace smoothing (add-one smoothing) to handle unseen or zero-count feature occurrences, preventing zero probabilities.

## Datasets Tested:
- *Test Dataset*: Taken from lesson slides to showcase if the implementation works.
- *Diabetes Dataset*: Simple dataset to predict diabetes results based on glucose and blood pressure.
- *Data Science Salary Dataset*: Dataset with various attributes (that are quite dependent, intentionally), that contains information about Data Scientist salaries.
