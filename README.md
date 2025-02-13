# House Price Prediction using XGBoost

## Overview
This project implements an **XGBoost (Extreme Gradient Boosting)** model to predict **house prices** based on various real estate features such as square footage, number of bedrooms, location, and more.

## Dataset
The dataset includes key attributes affecting house prices, such as:
- **Lot Size**
- **Number of Bedrooms & Bathrooms**
- **Square Footage**
- **Year Built**
- **Location & Neighborhood Features**
- **Market Trends**

## Model & Approach
- **Preprocessing**: Handled missing values, encoded categorical variables, and performed feature scaling.
- **Algorithm**: XGBoost Regression for price prediction.
- **Evaluation**: RMSE (Root Mean Square Error), MAE (Mean Absolute Error), and R² Score.

## Installation & Requirements
To run this project, install the necessary dependencies:

```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn
