# Iris Species Recognition

## Overview

In this project I utilize the famous [Iris Flower Data Set](http://en.wikipedia.org/wiki/Iris_flower_data_set) to classify the Iris flowers into three species - Iris setosa, Iris virginica and Iris versicolor. The dataset consists of 150 iris flower samples, each species having 50 samples each. Four features were measured sepal length (in cm), sepal width (in cm), petal length (in cm), petal width (in cm).

## Description

Here, the machine learning Model -  Support vector Machines is implemented. I am using seaborn and matplotlib for data visualisation and exploratory data analysis. The data is divided into 70 to 30 ratio for training and testing the model.


## Result and Conclusions

The model is evaluated using confusion matrix and classification report. The parameters were tuned further to achieve higher accuracy using GridSearchCV and an average accuracy of 98% was achieved for the test data set.
