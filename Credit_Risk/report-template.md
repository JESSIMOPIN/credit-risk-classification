# Module 12 Report 

## Overview of the Analysis

The goal of the analysis performed was to develop and evaluate machine learning models to predict loan status based on financial information. The data set names "lending_data.csv" contains 77,536 registers with previous targeted information of healthy and risky loans. The primary objective was to create a predictive capable model of loans classification.

As part of the data analysis, the following stages were involved:

1. Data loading and exploration: Adding the dataset into a Pandas DataFrame, after that I performed an exploratory analysis reviwing the first rows (head) to obtain basic information about the structure and complement with a .info() to get a better understanding of what it contains.
2. Data preparation: I identified the target variable and split it into features, after, the training and testing sets were created.
3. Model training: I choose a logistic regression model  and trained it on the training set.
4. Model evaluation: The trained model was used to predict loan status on the testing set. After that, confusion matrix and classification reports were used to evaluate the model's performance.

## Results

Confusion Matrix
[[37311   192]
 [  120  1145]]


Classification report


              precision    recall  f1-score   support

           0       1.00      0.99      1.00     37503
           1       0.86      0.91      0.88      1265

    accuracy                           0.99     38768
   macro avg       0.93      0.95      0.94     38768
weighted avg       0.99      0.99      0.99     38768

## Summary

Based on the analysis, the "logistic regression model" demonstrated promising results in predicting loan status. The precision and recall scores for both classes were evaluated to assess the model's performance.