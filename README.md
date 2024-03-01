#  Project-01-Big-Mart-Sales-Prediction
1) Problem Statement
The BigMart Data Science team has gathered sales data for the year 2013, comprising 1559 products across 10 stores located in various cities. The dataset also includes specific attributes for each product and store. The primary objective of this project is to develop a predictive model that can estimate the sales of each product at a given store.

Business Objective: The ultimate goal is to leverage the developed model to identify the product and store attributes that significantly impact sales, thereby aiding BigMart in devising strategies to enhance sales.

Analysis Approach

Type of problem: This is a supervised learning problem.
Target feature: Item_Outlet_Sales
We will handle this problem in a structured way following the table of contents given below:

1) Problem Statement
2) Hypothesis Generation
3) Loading Packages and Data
4) Data Structure and Content
5) Exploratory Data Analysis
6) Univariate Analysis
7) Bivariate Analysis
8) Missing Value Treatment
9) Feature Engineering
10) Encoding Categorical Variables
11) Label Encoding
12) One Hot Encoding
13) PreProcessing Data
14) Modeling
15) Linear Regression
16) Regularized Linear Regression
17) RandomForest
18) XGBoost
19) Predictions & Summary
20) Saving The Final Model
    
# PYTHON LIBRARY USED :
1) NumPy (imported as np) - for numerical operations and linear algebra.
2) pandas (imported as pd) - for data processing and manipulation.
3) math - for mathematical operations.
4) matplotlib.pyplot (imported as plt) - for creating visualizations.
5) seaborn - for statistical data visualization.
6) sklearn.impute - for handling missing values using KNN imputation.
7) klearn.preprocessing - for data preprocessing tasks like label encoding, polynomial feature generation, and standardization.
8) sklearn.pipeline - for creating pipelines for data preprocessing and model building.
9) sklearn.linear_model - for linear regression models like LinearRegression, ElasticNet, Lasso, and Ridge.
10) sklearn.ensemble - for ensemble learning methods like RandomForestRegressor.
11) sklearn.model_selection - for splitting data into training and testing sets, cross-validation, and hyperparameter tuning.
12) sklearn.metrics - for evaluating model performance using metrics like mean absolute error, mean squared error, and R-squared.
13) xgboost - for XGBoost regression models.
14) optuna - for hyperparameter optimization.
15) pickle - for serializing and deserializing Python objects.
16) warnings - for handling warnings.

# DOWNLOAD DATA SET
https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data


