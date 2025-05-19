# PRODIGY_ML_01
House Price Prediction using Linear Regression A simple machine learning project using Linear Regression to predict house prices based on square footage, bedrooms, and bathrooms. Built as part of the Prodigy InfoTech ML Internship Task 01 using the Kaggle House Prices dataset.
# PRODIGY_ML_01 - House Price Prediction using Linear Regression

This is Task 01 of the Prodigy InfoTech Machine Learning Internship. The objective is to build a simple linear regression model that predicts house prices based on key features from the Kaggle House Prices dataset.

## 📌 Project Overview

- Predict house prices using Linear Regression
- Dataset: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- Tools: Python, Pandas, Scikit-learn, Matplotlib, Joblib

## 🧠 Features Used
- `GrLivArea`: Above-ground living area in square feet
- `BedroomAbvGr`: Number of bedrooms
- `FullBath`: Number of full bathrooms

## 🚀 Steps Performed

1. Data loading and preprocessing
2. Feature selection
3. Model training using Linear Regression
4. Model evaluation with R² Score and Mean Squared Error
5. Model saving using `joblib`
6. Prediction on new inputs

## 🧪 Example Prediction

```python
input = [[2000, 3, 2]]
predicted_price = model.predict(input)
