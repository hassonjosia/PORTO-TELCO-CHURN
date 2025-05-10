📝 Notebook Overview
This notebook presents a complete supervised learning pipeline for predicting customer churn in a telecom company. It covers data preprocessing, feature engineering, and classification using models like Logistic Regression, Random Forest, KNN, Decision Tree, and XGBoost.

The project is designed to identify potential churners so that the company can take preventive actions to improve customer retention.

Highlights:

  - Clean and structured pipeline for churn prediction

  - Cross-validation and hyperparameter tuning

  - Model evaluation with accuracy, precision, recall, F1-score, and ROC AUC

  - Insight generation to support business decision-making

This project is a machine learning pipeline for predicting customer churn in a fictional telecommunications. It includes end-to-end analysis: from data cleaning and feature engineering to model building and evaluation.

🧠 Business Problem
Build a predictive model to identify customers who are likely to churn (i.e., leave the service). Understanding the patterns behind customer churn allows the business to proactively intervene and reduce attrition.

📊 Dataset Features
The dataset contains 21 columns, including:

- customerID: Unique customer identifier

- tenure: Months with the company

- Contract: Type of subscription (Month-to-month, One year, Two year)

- MonthlyCharges, TotalCharges: Billing data

- Churn: Target variable (Yes/No)

Plus demographic and service-related attributes like gender, InternetService, OnlineSecurity, etc.

🔧 Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)

- Scikit-learn (modeling, metrics, preprocessing)

- XGBoost

- Jupyter Notebook

👍 Key Steps
1. Data Exploration
  Overview of numerical and categorical features, missing values, and data types.

2. Data Preprocessing

  - Label encoding for binary categories

  - One-hot encoding for multi-class categories

  - Standardization using RobustScaler and StandardScaler

3. Feature Engineering
  Creating and selecting features based on correlations and domain understanding.

4. Model Building & Evaluation
  Models evaluated include:

  - Logistic Regression

  - Decision Tree

  - Random Forest

  - K-Nearest Neighbors

  - XGBoost

Evaluated with metrics like accuracy, ROC AUC, precision, recall, F1-score, and confusion matrix.

5. Model Optimization
Grid search for hyperparameter tuning and comparison of multiple models using cross-validation.

🏆 Model Highlights
Best Model: XGB

Top Features: tenure, Contract, TotalCharges, InternetService, TechSupport, etc.

📈 Visualizations
Includes ROC curve, feature importance plots, and correlation heatmaps to support interpretation.

👨‍💻 Author
hassonjosia
