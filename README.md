# credit-risk-classification
Module 20 Challenge

## Overview of the Analysis
The purpose of this analysis is to determine whether a logistic regression model can accurately predict the creditworthiness of borrowers. 

The financial information that was used to make predictions included the loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. By using this information, the model was able to predict whether a borrower could reliably receive a healthy loan, or if that loan would be high-risk. 

To build the model, I began by creating a training set and a testing set. The training set used all the information from the dataset to train and fit the logistic regression model, while the testing set was used to test its accuracy.  Once the model was created, a confusion matrix was used to determine the accuracy of the model.

## Results
Machine Learning Model 1:
•	Accuracy: According to the classification report, the model had an average of 99% accuracy.
•	Precision: The model was 100% precise when predicting the precision of healthy loans, and 87% precise for high-risk loans. The macro average of both combined is 94%, while the weighted average is 99%.
•	Recall: The model was 100% precise when predicting the recall of healthy loans, and 95% precise for high-risk loans. The macro average of both combined is 97%, while the weighted average is 99%.

## Summary
Based on the results, the logistic regression model can be trusted to predict the creditworthiness of borrowers. A 99% accuracy rate shows that while the model isn’t perfect, it has an extremely high success rate. Given that the outcome isn’t 100% accurate, I would recommend double checking the information manually before giving out a loan, but this information can be trusted to speed up the process and recognize which loans are most likely healthy or high-risk.

