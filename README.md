# BigMart Sales Prediction

## Problem Statement

Retail businesses need accurate sales forecasting to manage inventory, reduce losses, and improve decision-making. The goal of this project
is to predict the sales of products across different BigMart outlets based on product attributes and store 
information using Machine Learning techniques.

## Project Overview

This project uses the BigMart Sales dataset to build a machine learning model capable of predicting product sales. The dataset was
cleaned, preprocessed, analyzed, and used to train an XGBoost Regressor model. Hyperparameter tuning and
regularization techniques were applied to improve model performance and reduce overfitting.

## Dataset Information

- Dataset: BigMart Sales Dataset
- Total Records: 8,523
- Features: 12

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Project Workflow

1. Data Collection and Loading
2. Data Understanding
3. Handling Missing Values
4. Data Visualization
5. Feature Encoding
6. Feature and Target Separation
7. Train-Test Split
8. Model Training using XGBoost
9. Hyperparameter Tuning
10. Model Evaluation

## Model Performance

| Metric | Score |
|----------|----------|
| Training R² Score | 0.646 |
| Testing R² Score | 0.587 |

## Key Techniques Applied

- Missing Value Imputation
- Label Encoding
- Exploratory Data Analysis (EDA)
- Hyperparameter Tuning
- Regularization
- Model Performance Evaluation

## Conclusion

The XGBoost Regressor model was successfully trained to predict product sales. Model complexity was controlled using hyperparameter tuning and regularization, resulting in balanced training and testing performance with reduced overfitting.
