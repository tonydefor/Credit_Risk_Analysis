# Credit_Risk_Analysis

## Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we’ll need to employ different techniques to train and evaluate models with unbalanced classes. We're going to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, we'll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Analysis

Using our knowledge of the imbalanced-learn and scikit-learn libraries, we’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, we’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then we’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, we’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

## Summary


## Conclusion
