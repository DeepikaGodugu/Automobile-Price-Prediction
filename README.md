# Automobile Price Prediction Using Machine Learning

## Project Overview
This project uses machine learning regression techniques to predict automobile prices based on vehicle characteristics. It explores the factors that influence car prices and compares different models to identify the best-performing model.

## Objectives
- Perform Exploratory Data Analysis (EDA).
- Clean data and handle missing values.
- Detect and handle outliers using the IQR method.
- Encode categorical variables.
- Build and evaluate regression models.
- Identify important features affecting car prices.
- Predict prices for new car data.

## Dataset
The dataset contains automobile specifications such as:
- Make and fuel type
- Engine size and horsepower
- Vehicle dimensions
- Curb weight
- City and highway mileage
- Automobile price

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Data Preprocessing
- Handled missing values using median and mode imputation.
- Converted numerical columns into appropriate data types.
- Handled outliers using the IQR method.
- Applied One-Hot Encoding to categorical variables.
- Split the dataset into training and testing sets.

## Machine Learning Models
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Model Evaluation
Models were evaluated using:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

Random Forest achieved the best performance among the three evaluated models.

## Key Outcomes
- Compared three regression models.
- Identified important features influencing automobile prices.
- Saved the trained Random Forest model.
- Generated predictions for sample and new car data.

## Conclusion
This project demonstrates the application of machine learning in automobile price prediction through data analysis, preprocessing, model building, evaluation, and prediction.
