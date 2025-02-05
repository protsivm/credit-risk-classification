## Overview of the Analysis

* The goal of this analysis is to build a model that predicts whether a loan is safe or risky. 
* The dataset contained loan-related financial details, such as: [Loan size, Interest rate, Borrower income, Debt-to-income ratio, Number of accounts, Derogatory marks, Total debt]
* Variables that were predicted are "value_counts" -- Safe loans (0), Risky loans (1)
* Dataset was split into training and testing sets using "train_test_split" .
* The LogisticRegression model was trained on the training data. Predictions were made on the test data.

## Results

*Machine Learning Model:
* Accuracy: 99% of all loan predictions were correct.
* Precision for Safe Loans: 100% of loans predicted as safe were safe.
* Recall for Safe Loans: 99% of safe loans were correctly identified as safe.
* Precision for Risky Loans: 85% of loans predicted as risky were risky.
* Recall for Risky Loans: 95% of risky loans were correctly identified as risky.

## Summary

I recommend using this model.

The model is very accurate (99%).
The model successfully identifies 95% of risky loans.
The model wrongly indentified 15% of safe loans as risky, 
If the company’s main goal is to avoid risky loans, this model works well.
If the company wants to approve more loans, the model should be adjusted to reduce the number of safe loans misclassified as risky.
