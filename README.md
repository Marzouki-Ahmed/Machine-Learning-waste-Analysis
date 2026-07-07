# Machine Learning for Waste Generation Analysis

## Project Overview
This project analyzes waste generation across Irish economic sectors (NACE activities) using historical data from 2004 to 2020. The objective is to develop machine learning models capable of predicting waste generation while demonstrating the importance of data preprocessing, feature engineering, and model evaluation.

## Objectives
- Clean and preprocess the dataset.
- Perform Exploratory Data Analysis (EDA).
- Detect outliers using the IQR method.
- Validate data using the Central Limit Theorem (CLT).
- Compare multiple machine learning regression models.
- Predict waste generation using historical data.

## Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Machine Learning Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Results
| Model | R² Score |
|-------|----------|
| Linear Regression | Improved after One-Hot Encoding |
| Decision Tree Regressor | Improved performance |
| Random Forest Regressor | **0.7364** |

## Key Findings
- Removed redundant "Total" categories to avoid data leakage.
- Applied One-Hot Encoding to categorical variables.
- Random Forest achieved the best predictive performance.
- Data preprocessing significantly improved model accuracy.

## Dataset
- Source: Central Statistics Office (CSO) Ireland
- Period: 2004–2020

## Author
Ahmed Marzouki
marzoukiahmed.irl@gmail.com
