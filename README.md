Flight Price Prediction using Machine Learning

This project uses machine learning techniques to predict airline ticket prices based on flight details such as airline, source, destination, duration, and number of stops. The goal is to build a model that provides accurate flight price estimates to help users make cost-effective travel decisions.

This notebook includes:
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Saving and using the model for new predictions


   Dataset

- Description: Contains information about flight routes, duration, airline, and ticket prices.

Key columns:
- Airline
- Source
- Destination
- Route
- Total_Stops
- Dep_Time
- Arrival_Time
- Duration
- Price (target variable)

---

Workflow

1. Data Cleaning
   - Handling missing values
   - Dropping irrelevant features (Route,Additional_Info, etc.)
2. Feature Engineering
   - Encoding categorical variables
3. Model Building
   - Algorithms tried: Random Forest Regressor, Grid Search CV, Linear Regression, Ridge Regressor, XGBoost,etc.
   - Evaluation Metrics: RMSE, R² Score
4. Model Saving
   - Using joblib to save the trained model
  
Results
Achieved R2 Score of 0.9839 (98.39) on Test Set using Random Forest Regressor.
