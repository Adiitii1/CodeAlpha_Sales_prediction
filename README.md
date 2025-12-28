# Car Price Prediction Using Machine Learning

## Overview
This project predicts car selling prices using machine learning. It uses features such as Year, Present Price, Driven Kms, Fuel Type, Selling Type, Transmission, and Owner. The dataset is cleaned, preprocessed, and encoded for regression modeling.

## Dataset
- Columns: Car_Name, Year, Selling_Price, Present_Price, Driven_kms, Fuel_Type, Selling_type, Transmission, Owner
- Source: Public car price dataset (CSV)

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Joblib (for saving models)

## Steps
1. **Data Loading**: Load CSV file into a Pandas DataFrame.
2. **Data Cleaning**: Handle missing values and strip column spaces.
3. **Feature Selection**: Selected relevant features affecting car price.
4. **Encoding**: One-hot encoding for categorical features (Fuel_Type, Selling_type, Transmission).
5. **Train-Test Split**: Split dataset into training and testing sets (80-20).
6. **Model Training**: Train Linear Regression and optionally Random Forest Regressor.
7. **Predictions**: Predict selling prices using the trained model.
8. **Evaluation**: Evaluate model performance using MAE, MSE, RMSE, and R² score.
9. **Visualization**: Plot Actual vs Predicted prices.
10. **Insights**: Analyze how features influence car prices.
11. **Optional Improvements**: Use ensemble models, hyperparameter tuning, feature importance analysis.
12. **Save Model**: Save trained model for future use with Joblib.

## Key Insights
- Newer cars and higher present prices generally have higher selling prices.
- Higher driven kilometers reduce selling price.
- Fuel type, transmission, and ownership also affect pricing.
- Regression model predicts selling prices with reasonable accuracy.
- Random Forest Regressor can improve accuracy further.

## Real-World Applications
- Used car price estimation
- Insurance valuation
- Automotive resale platforms
- Market analysis for dealerships


