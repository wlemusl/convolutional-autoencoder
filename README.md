# convolutional-autoencoder
This project aims (1) to apply a convolutional autoencoder to extract a reduced number of critical features of time-series signals with length of 60 steps, and (2) to test different machine learning classification methods by using the reduced number of features as their input to classify each signal. Support Vector Machine, Random Forest, and Logistic Regression are the three tested machine learning classification models.

This repository contains one ipynb file and one csv file.

The only ipynb file is:
1. "autoencoder.ipnyb" - This code is used to explore the data, create a training and testing set, build the autoencoder, reduced the number of signals features, input the reduced number of features of each signal to the three classifiers, and test the three machine learning classification models.

The only csv file is:
1. "Synthetic control chart time series data.csv" - This is a filtered version of "synthetic_control.data", which can be found in UCI Machine Learning Repository, specifically: http://archive.ics.uci.edu/ml/datasets/Synthetic+Control+Chart+Time+Series. The original dataset includes a total of 600 records with 6 different labels of signals, but the csv file I provide is a filtered version with 300 records and only 3 different labels.
