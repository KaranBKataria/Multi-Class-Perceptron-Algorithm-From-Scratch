# Multi-Class-Perceptron-Algorithm-From-Scratch

Coding a multi-class perceptron algorithm from scratch to determine whether a dataset (with 6 classes) is perfectly linearly separable in the space defined by linear PCA and Kernel PCA. The code and implementation of both linear and kernel PCA was largely produced from scratch using Numpy and Pandas. Moreover, in order to perform hyperparameter tuning, a grid-search function was coded from scratch and was used to produce a heatmap. 

The purpose of this project was to investigate whether it was possible to categorise 6 classes representing 6 different accents (US, UK, GE, FR, ES, IT) into distinct regions separated by a linear classifier. 

Through implementing the multi-class perceptron on different feature spaces (original 12D, linear PCA and kernel PCA), it was found that perfect linear separability was possible in a feature space defined kernel PCA. This was possible for specific pairs of hyperparameters found via a grid search. These consisted of gamma values used as part of the Radial Basis Kernel (RBF) function used to compute Kernel PCA and the top number of Kernel Principal Components.
