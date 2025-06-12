# Customer-Churn-Prediction
# Churn Prediction

## Overview of the project
This project focuses on predicting customer churn using machine learning techniques. Customer churn refers to the phenomenon where customers stop using a company’s services. Predicting churn is a challenging yet crucial task for businesses, especially in sectors like telecom. The goal is to build a model that can predict which customers are likely to leave, allowing companies to take preventive actions. I have used models such as Logistic Regression, Random Forest, and XGBoost to predict churn effectively.

## Purpose of the project
The main aim of this project is to develop a reliable churn prediction model that helps businesses identify customers at risk of leaving. This prediction can be used to improve customer retention strategies, reduce losses, and improve overall customer satisfaction. The project is intended to support proactive decision-making in business operations using data-driven insights.

## Functionalities of the project
- Analyze customer demographics, service usage, and contract details to understand behavior patterns.
- Preprocess data: clean, encode categorical variables, and scale numerical features.
- Train and compare multiple machine learning models for predicting churn.
- Evaluate model performance using accuracy, ROC-AUC score, and confusion matrix.
- Use SHAP (SHapley Additive Explanations) to interpret model decisions and identify key factors influencing churn.

## Setup and running instructions

### Required libraries
Make sure the following Python libraries are installed:
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  
- xgboost  
- shap  
- imblearn  

### Steps for executing the code
1. Install and import all the required libraries listed above.
2. Download the Telco Customer Churn dataset from: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
3. Load the dataset and follow the preprocessing steps in the notebook.
4. Train the machine learning models provided in the code.
5. Evaluate the models and visualize the results using metrics and plots.
6. Use SHAP to visualize and understand model explainability.



