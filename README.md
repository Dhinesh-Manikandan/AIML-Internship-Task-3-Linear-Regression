# AIML-Internship-Task-3-Linear-Regression

# Overview
In this task, I implemented and explored both simple and multiple linear regression using a house price dataset. My goal was to understand the core concepts and evaluation metrics of regression models.

# Tools Used

Python 3.x

pandas

scikit-learn

matplotlib

# Dataset

Filename: Housing.csv

Description: Contains features like area (sq.ft), number of bedrooms ,etc.,.,

# Data Import and Preprocessing

I loaded the dataset using pandas.

I handled missing values (using median for numeric columns, mode for categorical columns).

I encoded categorical variables with one-hot encoding if needed.

I standardized numeric features for better model performance.

# Train-Test Split

I split the data into training and testing sets (typically 80% train, 20% test).

# Model Training

I used scikit-learn’s LinearRegression to train both simple and multiple regression models.

# Model Evaluation

I evaluated the models using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² (Coefficient of Determination)

# Visualization and Interpretation

I plotted the regression line (for simple regression).

I interpreted the regression coefficients to understand the relationship between features and sale price.

# References or Source: 

Dataset : Housing.csv
