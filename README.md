# Module 20 Challenge
## Instructions
* Split the Data into Training and Testing Sets
* Create a Logistic Regression Model with the Original Data
* Write a Credit Risk Analysis Report


# Module 20 Report Template

## Overview of the Analysis

The analysis's goal is to develop a model that can determine a borrower's creditworthiness by training and assessing a model based on loan risk. The dataset contains past loan activity from a peer-to-peer lender that concentrated on borrower income, loan amount, interest rate, and other factors. Using logistic regression as the approach, the data was divided into training and testing datasets, and the testing dataset was used to generate predictions for assessments.


## Results

* The overall model had an accuracy is 99%. This means that the prediction of our model was 99% correct

* Machine Learning Model 0:
    * Precision : 100% (The model was 100% correct when predicting good loans)
    * Recall : 99% (The model was very high at identifying the correct data points)

* Machine Learning Model 1:
    * Precision : 85% (The model was 85% correct when predicting high-risk loans)
    * Recall : 91% (The model was very high at identifying the correct data points)

## Summary

When predicting the loan labels classified as 0 (healthy) or 1 (high-risk), the logistic regression model had a 99% accuracy rate. The mismatch in our data, 619 for class 1 loans compared to 18765 for class 0 loans, makes the outcomes of our model's prediction of class 1 loans, evident.

We can observe from the confusion matrix that this model performs rather well because the diagonal values are fairly good, indicating that there is a high number between actual and predicted zero and actual and predicted one. Given that high risk loans carry a higher risk of loss, I highly recommend this model for predicting these kinds of loans.
