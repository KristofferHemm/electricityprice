# electricityprice

## Introduction
This dataset consists of raw data containing the current prices, as well as the predicted demand, for electricity in the regions New South Wales and Victoria. The dataset may contain some erroneous observations.
Our task is to clean the data and predict whether the price of electricity will rise or fall.  
The target feature is a binary, where 1 represents a price increase and 0 represents a fall in the price of electricity.  
Multiple machine learning models will be employed, and we will find the model with the highest degree of accuracy.

## Models
We will train the following models

Logistic regression
Support vector machines
Decision tree
Random forest
K-nearest neighbor

## Results
We observe that all models perform quite similarly, with an accuracy on the range of 0.75 to 0.80.  
The best performing model was random forest classifier, with an accuracy of 0.79.  
We got the best performance out of the random forest classifier when using gini criterion, a max depth of 12 and 100 trees.