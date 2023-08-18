# fuel-consumption-analysis-with-machine-learning

This repository contains the analysis of the "auto-mpg.data" dataset using various machine learning techniques. The dataset consists of 7 features: cylinder count, displacement, horsepower, weight, acceleration, model year, and origin. The goal of this analysis is to perform Exploratory Data Analysis (EDA), Feature Engineering, Data Splitting and Standardization, as well as applying Linear Regression and Regularization algorithms to predict the miles per gallon (mpg) of vehicles.

## Dataset
The "auto-mpg.data" dataset is used for this analysis. It includes information about various car models and their attributes. The features are as follows:

Cylinder Count
Displacement
Horsepower
Weight
Acceleration
Model Year
Origin
The target variable we are trying to predict is miles per gallon (mpg).

## Contents
The repository is organized as follows:

data: Contains the "auto-mpg.data" dataset in CSV format.
notebooks: Jupyter notebooks detailing the step-by-step analysis process.
results: Visualizations and outputs generated from the analysis.
README.md: This document, providing an overview of the project.

## Analysis Steps
### Exploratory Data Analysis (EDA):
Summary statistics of the dataset.
Distribution of features and target variable.
Correlation analysis among features.
### Feature Engineering:
Handling missing values and outliers.
Encoding categorical features (if applicable).
### Data Splitting and Standardization:
Splitting the dataset into training and testing sets.
Standardizing features to have mean of 0 and variance of 1.
### Linear Regression:
Applying linear regression to predict mpg.
Evaluating model performance using metrics such as mean squared error.
### Regularization Algorithms:
Exploring L1 (Lasso) and L2 (Ridge) regularization techniques.
Tuning hyperparameters and comparing model performance.
