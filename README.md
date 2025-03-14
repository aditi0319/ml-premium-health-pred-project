# Health Premium Prediction - Regression Model
## Overview
This project aims to predict health insurance premiums based on various customer attributes using a regression model. It follows a structured workflow including scope definition (Jira), data collection, data cleaning & EDA, feature engineering, model training, error analysis, and finally, deployment using Streamlit.

## Table of Contents
Project Scope
Dataset
Exploratory Data Analysis (EDA)
Feature Engineering
Model Training
Error Analysis
Deployment
Installation & Usage
Results & Insights
Future Improvements
Contributors
Project Scope
Defined tasks and workflow using Jira for effective project management.
Developed a machine learning model to predict health insurance premiums based on customer demographics and medical history.
Built an interactive Streamlit web app to allow users to input data and get real-time premium predictions.
Dataset
The dataset was collected from [source name if available].
Features include:
Age
Gender
Region
Marital_status
BMI_Category
Smoking_Status
Employment_Status
Income_Level
Income_Lakhs
Medical History
Insurance_Plan
Annual_Premium_Amount
Performed data cleaning to handle missing values, outliers, and inconsistent data.
Exploratory Data Analysis (EDA)
Conducted initial analysis using Matplotlib and Seaborn.
Visualized correlations between features and the target variable.
Identified patterns such as higher premiums for smokers and individuals with higher BMI.
Feature Engineering
Encoded categorical variables using One-Hot Encoding.
Scaled numerical features using StandardScaler.
Created new features like BMI category and smoker risk factor.
Model Training
Split data into train and test sets (80:20 ratio).
Used regression models:
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
XGBoost
Evaluated models using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.
Error Analysis
Identified high-error predictions using residual plots.
Used SHAP (SHapley Additive Explanations) to understand feature importance.
Improved performance by tuning hyperparameters using GridSearchCV.
Deployment
Built a Streamlit web app for real-time premium predictions.
User can input details and receive an instant premium estimate.
Hosted on [Streamlit Cloud / AWS / Heroku] (provide link if deployed).

