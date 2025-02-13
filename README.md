Overview

  This project aims to predict customer churn using machine learning techniques. 
  By analyzing customer behavior and service usage patterns, the model identifies customers who are likely to leave, helping businesses take proactive measures to retain them.

Dataset

  Source: Telco Customer Churn Dataset (Kaggle)

  Description: The dataset contains information about customers, including demographics, account details, and service usage.

  Target Variable: Churn (Yes/No)


Technologies Used

  Programming Language: Python

  Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost


Project Workflow

  1. Data Preprocessing

  Handling missing values

  Encoding categorical features

  Feature selection and scaling



  2. Exploratory Data Analysis (EDA)

  Visualizing customer demographics and churn distribution

  Correlation analysis of features


  3. Model Development

  Implemented multiple classification models:

  Logistic Regression

  XGBoost (Best performing model)


  Addressed class imbalance using SMOTE

  Hyperparameter tuning with GridSearchCV



  4. Model Evaluation

  Metrics used: Accuracy, MAE , MSE.

  Confusion matrix analysis

  Results

  Best model: XGBoost

  Achieved 76 % accuracy 

  Feature importance analysis shows that contract type, tenure, and monthly charges are key indicators of churn
