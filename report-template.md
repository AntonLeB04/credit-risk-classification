## Overview of the Analysis

The reason for this analysis is to determine the credit worthiness of borrowers. The financial data that was used was loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, loan status. The stages that I went through to get the machine learning were splitting the data, creating x and y labels from the loan status column, checking the balance of the labels value y, splitting the data into training and testing datasets. Once creating the training and testing datasets, the utilization of Logistic Regression Model was used. Starting with fitting the x_train and y_train into a logistic regression model. Then there were predictions that were on the testing data labels by using the testing feature data X_test and the fitted model. Following that step, the evaluation of the model was conducted by finding the accuracy score of the model, generation of a confusion matrix, and the classification report. `LogisticRegression` was used and this method computes the probability of an event occurring.

## Results

  Machine Learning Model Results:
  Healthy Loans
    * Precision = 1.00
    * Recall = 0.99
    * F1-Score = 1.00
  High Risk Loans
    * Precision = 0.84
    * Recall = 0.94
    * F1-Score = 0.89

The balance accuracy score is 0.99 for the model over all. Meaning when dealing with healthy loans, we can be certain that the borrower will be able to repay the loan and with the risky loans there needs to be more caution due to the fact that there is potential profit in the misdiagnosed risky loan.



## Summary
Overall the model is very effective for determining the healthy loans which is very important so financial institutions don't miss out on potential profit. But the inaccuracies in the risky loans are something that should be further investigated. It is very important to avoid risky loans since that can lead to nationwide financial problems, like what was seen in the 2007-2008 housing crisis with risky mortgaging practices.