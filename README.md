# Prediction-of-lending-club-loan-Defaulters
To identify loan defaulter's so that lending club can decide whether a person is fit for sanctioning a loan or not in the future.

# Indian Paper Curreny Prediction :india: 

## Table of Content
  * [Overview](#overview)
  * [Dataset](#Dataset)
  * [Feature Information](#Feature Information)
  * [Libraries used](#Libraries_used)
  * [Pipelines created](#Pipelines_created)




## Overview
* Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
* Lending clubs are taking risk by lending loans to applicants who will not be able to repay the loan amount.The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.
* In this project, we will be working on exploring and crunching out the driving factors behind the loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

## Dataset
These files contain complete loan data for all loans issued through the 2007-2011, including the current loan status (Current, Charged-off, Fully Paid, etc.) and latest payment information. The file containing loan data through the "present" contains complete loan data for all loans issued through the previous completed calendar quarter. Additional features include credit scores, number of finance inquiries, and collections among others. The file is a matrix of about 39 thousand observations and 111 variables. A data dictionary is provided in a separate file.

## Feature Information
* Loan Variables such as loan amount, term, interest rate, etc which shows the information about the loan that will help us in finding loan default.

* Profile Variables such as employment status, relationship status, etc. which shows the information about the borrower profile which is not useful for us.

* Miscellaneous Variables such as geographic, EMI, delinquency, etc. which shows the information which is updated after providing the loan which in our case is not useful as we    need to decide whether to provide loan or not by default analysis.

## Libraries used
* Numpy
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn
* Statsmodels

## Pipelines created
* Data Collection - Data taken from Kaggle
* Feature Engineering - Data mining, Data cleaning , Data Exploration
* Feature Selection  - Backward Elimination and Forward Selection methods
* Classification Model Creation - All Base Models are built.
* Model Hyperparameter Tuning  - Using GridsearchCV best hyperparameters for each model are found.
* Comparison of classification models based on various metrics
* Model with best F1-Score is selected




