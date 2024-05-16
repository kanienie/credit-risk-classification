# credit-risk-classification
## Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

## NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

## Summary:
## How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

 The logistic regression model is excellent at predicting healthy loans (label 0) and does so with perfect accuracy. However, it’s slightly less accurate with high-risk loans (label 1). For high-risk loans, it correctly identifies about 87% of them and successfully finds 89% of all actual high-risk loans.

This small difference happens because there are many more healthy loans than high-risk loans. Despite this, the model is still very accurate overall and works well for both types of loans. The model’s ability to identify high-risk loans could be improved with further adjustments or by using methods to better handle the imbalance between the two types of loans.
