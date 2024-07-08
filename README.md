# SalesPrediction-Python-Machine-Learning-Regression-XGBoost

# Project Overview
This project aims to predict sales for a retail store using machine learning regression techniques, specifically focusing on XGBoost. The goal is to create a model that can accurately forecast sales based on various features of the products and stores.

**Python Packages Used:** Numpy,Pandas,Matplotlib,Seaborn,Scikit-Learn,XGBoost

# Introduction
Retail sales prediction is crucial for inventory management, resource allocation, and maximizing profits. This project utilizes regression techniques to build a predictive model that can estimate the sales of different products in various retail stores. The primary machine learning model used in this project is XGBoost, known for its high performance and accuracy.

# Dataset
The dataset used in this project includes various features such as: 'Item_Identifier', 'Item_Weight', 'Item_Fat_Content', 'Item_Visibility','Item_Type', 'Item_MRP', 'Outlet_Identifier',
'Outlet_Establishment_Year', 'Outlet_Size', 'Outlet_Location_Type' ,'Outlet_Type', 'Item_Outlet_Sales'.

# Process
1. Understanding the data 
2. Identification and imputation of missing values
3. Visualizing categorical and Numerical columns using Seaborn and Matplotlib
4. Used Label Encoder to convert categorical columns into numerical columns
5. Used XGBRegressor to train and test the data

# Model Evaluation
The model is evaluated using the R-squared metric. The training and testing scores indicate the model's performance:
1. Training R^2 Score: 0.8388
2. Testing R^2 Score: 0.2663
   
The discrepancy between the training and testing scores suggests potential overfitting. Various techniques such cross-validation, regularization, and feature selection are to be explored to improve the model's performance.
     
