# Credit-Card-Fraud-Detection

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

To Identify: - Fraudulent credit card transactions.

## Source - Kaggle

https://www.kaggle.com/mlg-ulb/creditcardfraud

Download the dataset in .csv format and name it as 'creditcard.csv' and save it where 'card_fraud.ipynb' file is cloned.

## Project Overview

1- Exploratory Data Analysis - EDA

2- Data Visualization

3- Outliers Detection

4- Data Pre-processing and Decomposition

Logistic Regression on original data


#### Resampling

5- Undersampling - TomekLinks

Logistic Regression on undersampled data

6- Oversampling - SMOTE (Synthetic Minority Over-sampling Technique)

Logisitc Regression on oversampled data


#### Using different Machine Learning Algorithms on Undersampled data:

7- K Nearest Neighbors (KNN) Classifier

8- Random Forest Classifier

9- Naive Bayes Classifier

10- Support Vector Machine (SVM)

11- Results and Comparison
