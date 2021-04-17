# Prediction-of-lending-club-loan-Defaulters
To identify loan defaulter's so that lending club can decide whether a person is fit for sanctioning a loan or not in the future.


## Table of Content
  * [Overview](#overview)
  * [Dataset](#Dataset)
  * [Feature_Information](#Feature_Information)
  * [Libraries_used](#Libraries_used)
  * [Pipelines_created](#Pipelines_created)




## Overview

* Lending clubs are taking risk by lending loans to applicants who will not be able to repay the loan amount.The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.

* The aim of the project is to predict a loan default while awarding of loan by creating a data based model which will be able to analyse the data and confirm the result to decide before awarding of loan .The importance of this business problem has a direct impact on a bank’s performance so as to avoid a situation of NPA and write-off / legal situation for handling a default on a loan. This has direct bearing on the bank’s performance and it’s balance sheet and market value and results in business growth.

* In this project, we will be working on exploring and crunching out the driving factors behind the loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

## Dataset

* These files contain complete loan data for all loans issued through the 2007-2011, including the current loan status (Current, Charged-off, Fully Paid, etc.) and latest payment information. 
* The file containing loan data through the "present" contains complete loan data for all loans issued through the previous completed calendar quarter. Additional features include credit scores, number of finance inquiries, and collections among others. The file is a matrix of about 39 thousand observations and 111 variables. A data dictionary is provided in a separate file.
Kaggle Link - https://www.kaggle.com/imsparsh/lending-club-loan-dataset-2007-2011

## Feature_Information
* Loan Variables such as loan amount, term, interest rate, etc which shows the information about the loan that will help us in finding loan default.

* Profile Variables such as employment status, relationship status, etc. which shows the information about the borrower profile which is not useful for us.

* Miscellaneous Variables such as geographic, EMI, delinquency, etc. which shows the information which is updated after providing the loan which in our case is not useful as we    need to decide whether to provide loan or not by default analysis.

## Libraries_used
* Numpy
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn
* Statsmodels

## Pipelines_created
* Data Collection - Data taken from Kaggle
* Feature Engineering - Data mining, Data cleaning , Data Exploration
* Feature Selection  - Backward Elimination and Forward Selection methods
* Classification Model Creation - All Base Models are built.
* Model Hyperparameter Tuning  - Using GridsearchCV best hyperparameters for each model are found.
* Comparison of classification models based on various metrics
* Model with best F1-Score is selected




