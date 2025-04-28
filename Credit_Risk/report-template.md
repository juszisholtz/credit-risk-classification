# Module 12 Report Template

## Overview of the Analysis

In this analysis, I built a machine learning model to predict the credit risk of borrowers using historical lending data from a peer-to-peer lending service. The goal was to classify loans as either healthy (label 0) or high-risk (label 1) based on the features provided in the dataset.
The dataset included various financial attributes related to borrowers, such as loan amounts, payment history, and borrower information. The target variable we needed to predict was the loan status, which indicates whether the loan is healthy (0) or high-risk (1).

The stages of the machine learning process involved:
1.	Data Preprocessing: Loading the data, cleaning it, and splitting it into features (X) and labels (y).
2.	Model Selection: I used Logistic Regression due to its suitability for binary classification tasks.
3.	Model Evaluation: I evaluated the model’s performance using a confusion matrix and classification report, assessing accuracy, precision, and recall.
The Logistic Regression model was used to train on the training dataset and then tested on a separate test dataset to ensure its effectiveness.


## Results

The results from the Logistic Regression model are summarized below:

Machine Learning Model 1: Logistic Regression

- Accuracy: 99%
- Precision for Healthy Loans (0): 1.00
- Recall for Healthy Loans (0): 0.99
- Precision for High-Risk Loans (1): 0.85
- Recall for High-Risk Loans (1): 0.95
- F1-Score for Healthy Loans (0): 1.00
- F1-Score for High-Risk Loans (1): 0.89

## Summary

The Logistic Regression model performed very well overall, with an accuracy of 99%. It achieved a high recall of 0.99 for healthy loans, meaning it correctly identified almost all healthy loans, which is important because incorrectly labeling a healthy loan as high-risk could have financial consequences.
For high-risk loans, while the model had a slightly lower precision of 0.85, it performed well in terms of recall (0.95), meaning it successfully identified most high-risk loans. The F1-Score for high-risk loans was 0.89, which indicates a reasonable balance between precision and recall.
Considering the high performance of the model, I would recommend using the Logistic Regression model for this classification task. However, it might also be worth exploring other models just to get a sense of their accuracy as well.
Overall, the model is well suited for this task, as correctly identifying both healthy and high-risk loans is important for reducing defaults and minimizing financial loss.
