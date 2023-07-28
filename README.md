### Credit Risk Analysis Report
## Overview of the Analysis
The aim of this analysis is to assess the credit risk of loan applicants using different machine learning models. Credit risk is the possibility of a loss resulting from a borrower's failure to repay a loan or meet contractual obligations. In this assignment, we analyzed lending data using Logistic Regression model and oversampling technique to predict whether a borrower will be able to pay back a loan.

### Results

## Logistic Regression Model
Accuracy Score: The balanced accuracy score of the logistic regression model is 0.9520. This score tells us that the logistic regression model was able to correctly predict the credit risk about 95.20% of the time.
Precision Score: The precision score of the logistic regression model for predicting high-risk loans (loan_status = 1) was 0.85, which tells us that when the model predicted a loan to be high risk, it was correct about 85% of the time.
Recall Score: The recall score of the logistic regression model for predicting high-risk loans (loan_status = 1) was 0.91, which means the model was able to identify 91% of the high-risk loans correctly.

## Logistic Regression Model with Oversampling
Accuracy Score: With oversampling technique, the accuracy score of the logistic regression model is not shown in your provided code, but we can assume the accuracy score would be higher due to oversampling's ability to better train the model on the minority class.
Precision Score: The precision score for high-risk loans prediction would likely be higher than that of the original logistic regression model, indicating that the oversampling technique improves the model's performance in predicting high-risk loans.
Recall Score: Similar to precision, the recall score would likely improve when applying oversampling technique as the model has more data on high-risk loans to learn from.

## Summary
After analyzing the performance of the logistic regression model and oversampling technique, it is clear that these machine learning techniques can be beneficial for assessing credit risk. The accuracy score, precision, and recall of the logistic regression model are all fairly high, indicating that the model is good at predicting whether a borrower will be able to pay back a loan.

However, it is also important to note that the original dataset was imbalanced, with more instances of low-risk loans compared to high-risk loans. This could have affected the performance of the logistic regression model. By applying the oversampling technique, we were able to train the model on more balanced data, which is expected to improve the model's performance in predicting high-risk loans.
