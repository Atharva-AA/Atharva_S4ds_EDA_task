# Atharva_S4ds_EDA_task
This is a EDA performed on Fifa dataset from 2017-2023 where I have considered and prejudiced that it will be used for display purpose or to determine the value of player so used the latest and given it priority
This repository contains an exploratory data analysis (EDA) and predictive modeling project on the FIFA dataset. The goal of this project is to analyze player attributes, uncover patterns, and build models to predict player values.



**Dataset**

The dataset used is a publicly available FIFA dataset containing player information, including:
// Player name, age, nationality, and club
// Player attributes (e.g., shooting, passing, dribbling, defending)
// Market value and wage
// Physical attributes (height, weight, etc.)

Note: Some preprocessing was done to clean missing values and remove irrelevant columns.

**Project Overview**

The project workflow included:

**Data Cleaning & Preprocessing**
// Removed rows with more than 50% missing values
// Handled missing values in numeric and categorical columns
// Converted data types where necessary (e.g., price strings to floats)

**Exploratory Data Analysis (EDA)**
// Analyzed distributions of player attributes
// Explored correlations between attributes and player value
// Visualized top players, clubs, and nationalities

**Feature Engineering**
// Created derived features like overall rating, age categories, and positional stats

**Modeling**
// Implemented multiple regression models: Linear Regression, Lasso & Ridge Regression, Random Forest Regressor
// Evaluated models using R² and RMSE
// Identified Random Forest as the best-performing model

**Model Improvement**
// Performed hyperparameter tuning and cross-validation for better accuracy
// Feature importance analysis to identify key predictors of player value

**Results**

Model	R² Score	RMSE
Random Forest	0.985	126,831
Linear Regression	0.919	292,578
Lasso Regression	0.919	292,578
Ridge Regression	0.918	292,600

Random Forest provided the most accurate predictions with the lowest RMSE.

**Visualization**

The repository includes visualizations such as:
// Distribution of player attributes
// Top clubs and nationalities by market value
// Correlation heatmaps
// Feature importance plots from Random Forest

**Conclusion**

The analysis reveals key insights about FIFA players’ market value, with overall rating, age, and certain attributes significantly affecting player valuation. The Random Forest model can be used for predicting player values based on their attributes with high accuracy.
