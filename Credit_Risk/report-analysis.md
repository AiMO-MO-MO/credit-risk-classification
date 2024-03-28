# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

- Utilizing lending data, we evaluated loan risk using a machine learning model. 
- Features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt were utilized in the analysis.
- The model was trained on historical data to predict whether a loan is classified as Healthy or High Risk. 
- The dataset was divided into training and test sets, and a Logistic Regression model was employed to fit the data and make predictions.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

- **Machine Learning Model 1:**
    - Healthy Loan:
        - Precision: 100%
        - Recall: 99%
        - F1-score: 100%
    - High-Risk Loan:
        - Precision: 85%
        - Recall: 91%
        - F1-score: 88%

## Summary

Summarize the results of the machine learning models and include a recommendation on the model to use, if any. For example:

- The Machine Learning Model trained on Lending Data effectively predicts Healthy Loans with high accuracy and precision. However, its performance in identifying High-Risk Loans is less optimal, showing lower precision and recall scores. Depending on the user's tolerance for misclassification, the model could still be useful for identifying High-Risk loans. It's worth noting that the training data may have been imbalanced, with fewer examples of High-Risk loans. With a larger and more balanced dataset, the model's performance in identifying High-Risk loans could potentially improve.

