# Machine-Learning-Classification-and-Regression

This repository contains code for a machine learning project focused on implementing logistic regression, support vector machines (SVM), and multi-class logistic regression. The project uses the MNIST dataset for classification tasks.

Project Structure
mnist_all.mat: MATLAB file containing the MNIST dataset.
script.py: Python script with functions for logistic regression, SVM, and multi-class logistic regression, including preprocessing of data.

Implementation Details
preprocess(): Function to load and preprocess the MNIST dataset, including feature selection, normalization, and data splitting.
blrObjFunction(): Computes the logistic regression error function and gradient using gradient descent optimization.
blrPredict(): Predicts labels using logistic regression weights.
mlrObjFunction(): Computes the multi-class logistic regression error function and gradient.
mlrPredict(): Predicts labels using multi-class logistic regression weights.
Results and Evaluation
The project evaluates the performance of logistic regression, SVM, and multi-class logistic regression on training, validation, and testing datasets.
