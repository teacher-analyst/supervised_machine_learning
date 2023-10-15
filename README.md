# Credit Risk Analysis Report

## Overview of the Analysis
As part of module 20 challenge of the Monash University Data Analytics Bootcamp, I am tasked with building a logistic regression model that can identify the creditworthiness of borrowers. The lending_data.csv file contains historical data from a peer-to-peer lending service company such as borrower income, loan size, interest rate, total debt and loan status. The loan status column has values of 0 and 1 which represent a healthy loan and high-risk loan respectively. The model tries to predict the creditworthiness by displaying a value of 0 or 1. Based on the model's predictions and actual loan status, an assessment is made about the effectiveness of the model. 

## Results

The results of the classification report are:

**Healthy Loan:**
- precision: 1
- recall: 1

**High-risk Loan**
- precision: 0.87
- recall: 0.89

The overall accuracy is 0.99. 

## Summary

For a lending service company, it is important to identify borrowers that are classified as high-risk. The logistic regression model perfectly predicts healthy borrowers with a precision and recall result of 1 and accuracy of 0.99. However, the model has a lower result when predicting high-risk borrowers at 0.87 precision and 0.89 recall. In addition, according to the confusion matrix, the model returned 67 false negatives meaning 67 loans were high risk but were predicted to be healthy. 

Therefore, the lending service company is recommended to use the logistic regression model to identify healthy loans only. 


