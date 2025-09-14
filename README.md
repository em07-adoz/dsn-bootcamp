# 🚗 Used Car Price Prediction - DSN Bootcamp Qualification Hackathon 2025

This repository contains my submission for the **DSN Bootcamp Qualification Hackathon 2025**, an all-expense-paid bootcamp competition.  
The goal was to build a machine learning model to predict the price of used cars based on different features such as brand, model, year, fuel type, mileage, and more.


## 📊 Problem Statement
Used cars are sold every day, but their prices can vary greatly depending on multiple attributes.  
The challenge was to **predict the selling price of a car** given its features.  
Submissions were evaluated using **Root Mean Squared Error (RMSE)**.

## 🔑 Approach
1. **Exploratory Data Analysis (EDA)**  
   - Checked distributions, missing values, and outliers.  
   - Identified important features like year, mileage, brand, fuel type, and transmission.  

2. **Data Preprocessing**  
   - Filled missing values (median for numeric, mode for categorical).  
   - Encoded categorical variables using label encoding and one-hot encoding.  
   - Normalized numerical values where necessary.  

3. **Modeling**  
   - Tried multiple models:  
     - Linear Regression (baseline)  
     - Random Forest Regressor  
     - XGBoost  
     - LightGBM  
   - Tuned hyperparameters for better performance.  

4. **Evaluation**  
   - Used **Root Mean Squared Error (RMSE)** as the metric.  
   - Performed cross-validation to avoid overfitting.  


