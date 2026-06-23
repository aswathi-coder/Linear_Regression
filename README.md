# California Housing Price Prediction using Regression Algorithms
# Project Overview
This project focuses on predicting California housing prices using supervised machine learning regression techniques.
Dataset used is California Housing Dataset available from Scikit-Learn.
The main objective is to build and compare different regression models to predict the house value based on various housing-related features.
The following regression algorithms are implemented and evaluated:
- Linear Regression
- Decision Tree Regressor
The performance of each model is compared using evaluation metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.
# Dataset Description
The California Housing Dataset contains information about houses in different regions of California.
The dataset consists of multiple housing-related features that influence house prices.
## Features Used:
- MedInc - Median income of residents
- HouseAge - Median age of houses
- AveRooms - Average number of rooms
- AveBedrms - Average number of bedrooms
- Population - Population of the area
- AveOccup - Average occupancy
- Latitude - Geographic latitude
- Longitude - Geographic longitude
## Target Variable:
House Value
# Data Preprocessing Steps
1. Handling Missing Values
2. Feature Scaling using StandardScaler
# Algorithms Used
## 1. Linear Regression
Linear Regression is a supervised learning algorithm that predicts the target variable by finding the best linear relationship between input features and output.
It works by fitting a straight-line equation that minimizes prediction errors.
It is suitable when the relationship between input variables and target value is approximately linear.
## 2. Decision Tree Regressor
Decision Tree Regression predicts values by splitting the dataset based on decision rules.
The model creates a tree-like structure where each branch represents a decision based on feature values.
It can capture non-linear relationships between features and target values.
# Model Evaluation Metrics
##1. Mean Squared Error (MSE)
##2. Mean Absolute Error (MAE)
##3. R² Score
The best-performing model was identified based on:
- Lowest MSE
- Lowest MAE
- Highest R² Score
# Results and Insights
Based on the evaluation metrices the Decision Tree Regressor is the best model.
