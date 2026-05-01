📌 Project Overview
This project is developed as part of the CodeAlpha Data Science Internship Task.
The goal is to build a machine learning model that can predict the selling price of used cars based on various features such as car age, mileage, fuel type, transmission, and ownership history.

The project demonstrates the full ML pipeline including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and evaluation.

🎯 Objective
Predict the selling price of used cars using regression models
Analyze key factors affecting car pricing
Compare multiple machine learning algorithms
Select the best-performing model based on evaluation metrics
📊 Dataset Information
The dataset contains information about used cars with the following features:

Feature	Description
Car_Name	Name/model of the car
Year	Manufacturing year
Selling_Price	Target variable (price in lakhs)
Present_Price	Current showroom price
Driven_kms	Total kilometers driven
Fuel_Type	Petrol / Diesel / CNG
Selling_type	Dealer or Individual
Transmission	Manual or Automatic
Owner	Number of previous owners
🛠️ Tech Stack
Python 🐍
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn
Machine Learning Models:
Linear Regression
Ridge Regression
Lasso Regression
Support Vector Regressor (SVR)
K-Nearest Neighbors Regressor
🔄 Workflow
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Car Age creation
Encoding categorical variables
Model Training
Hyperparameter Tuning using GridSearchCV
Model Evaluation
Model Selection
🏆 Best Model
Model: SVR (Support Vector Regressor)
Test R² Score: ~0.94
MAE: ~0.48
RMSE: ~0.82
The SVR model performed best due to its ability to capture non-linear relationships in the dataset.

📈 Key Insights
Present Price is the strongest predictor of Selling Price
Car Age significantly impacts price depreciation
Mileage (Driven_kms) negatively affects price
Manual cars dominate the dataset
Dealers tend to sell higher-priced cars than individuals# CodeAlpha_CarPricePrediction-
