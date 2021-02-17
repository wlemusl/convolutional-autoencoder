# convolutional-autoencoder
This project aims (1) to apply a convolutional autoencoder to extract a reduced number of critical features of time-series signals with length of 60 steps, and (2) to test different machine learning classification methods by using the reduced number of features as their input to classify each signal. Support Vector Machine, Random Forest, and Logistic Regression are the three tested machine learning classification models.

This repository contains one ipynb file and one csv file.

The only ipynb file is:
1. "autoencoder.ipnyb" - This code is used to explore the data, create a training and testing set, build the autoencoder, reduced the number of signals features, input the reduced number of features of each signal to the three classifiers, and test the three machine learning classification models.

The unique csv file is:
1. "Synthetic control chart time series data.csv" - This is a filtered version of "synthetic_control.data" and contains 300 records and 3 different labels of signals. However, the original dataset includes a total of 600 records and 6 different labels of signals. It can be found in UCI Machine Learning Repository: http://archive.ics.uci.edu/ml/datasets/Synthetic+Control+Chart+Time+Series
