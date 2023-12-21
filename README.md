#CodeClauseInternship_loan_prediction

This project aims to predict whether a loan application will be approved or not using historical loan application data.

## Data set(Taken from kaggle)
The loan_data.csv file contains data on loan applications including details like gender, marital status, income, loan amount, credit history etc. as well as the final loan status (approved/not approved).

## Goal
The goal is to build a machine learning model that can accurately predict if a new loan application will be approved or not based on the application details.

## Methods
* Exploratory data analysis to understand data distributions, correlations, missing values etc. 
* Data cleaning and preprocessing 
* Trying out different ML algorithms like logistic regression, random forests, SVM etc. and tuning their hyperparameters
* Evaluating model performance using AUC-ROC, precision, recall etc. 
* Selecting and optimizing the best performing model
* Building a prediction pipeline for new loan applications

## Conclusion
The random forest model achieved the best performance with an AUC-ROC of 0.92 on the test set. A flask API was built to expose the model to provide loan eligibility predictions on new data.

Further enhancements can be made by adding more data and trying more advanced model architectures.
