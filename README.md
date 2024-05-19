# PRODIGY_ML-01
# House Price Prediction Using Linear Regression
## Overview
This project demonstrates the application of linear regression for predicting house prices using the "train.csv" and "test.csv" datasets. The goal is to build a predictive model that can accurately estimate the price of a house based on various features.

## Primary Goal
The primary goal of this project is to develop a linear regression model to predict house prices. This involves data preprocessing, feature engineering, model training, evaluation, and generating predictions for a test set.

## Dataset
The datasets used in this project are "train.csv" and "test.csv." The "train.csv" file contains the training data, which includes various features and the target variable (SalePrice). The "test.csv" file contains the test data, which includes the features but not the target variable.

## train.csv
The training dataset contains the following columns:

Id: Unique identifier for each house
MSSubClass: The building class
MSZoning: The general zoning classification
LotFrontage: Linear feet of street connected to the property
LotArea: Lot size in square feet
Street: Type of road access
Alley: Type of alley access
LotShape: General shape of the property
... (other columns with house features)
SalePrice: The property's sale price
## test.csv
The test dataset contains the same columns as the training dataset except for SalePrice.

## Approach
The main steps in this project include:

## 1. Data Preprocessing
Exploring the dataset
Selecting relevant features based on correlation with SalePrice
Handling missing values
Creating new features (e.g., TotalBath, TotalSF)
## 2. Splitting the Dataset
Splitting the data into training and testing sets
## 3. Preprocessing Pipeline
Imputing missing values
Scaling the features
## 4. Model Training
Training a linear regression model
Optionally training other models like RandomForestRegressor for comparison
## 5. Model Evaluation
Evaluating the model using metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE)
Performing cross-validation
## 6. Predictions
Generating predictions for the test dataset
Preparing the submission file
## Files
train.csv: Training dataset

test.csv: Test dataset

sample_submission.csv: Sample submission file

house_price_prediction.py or house_price_prediction.ipynb: Python script or Jupyter notebook
containing the code for data preprocessing, model training, and evaluation
