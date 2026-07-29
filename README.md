🛡️ Credit Card Fraud Detection using Machine Learning
📌 Overview

This project builds a Machine Learning model to detect fraudulent credit card transactions. Since fraud cases are extremely rare, the project focuses on handling class imbalance using SMOTE and compares multiple classification algorithms to identify the best-performing model.

🎯 Objectives
Detect fraudulent transactions
Perform Exploratory Data Analysis (EDA)
Handle class imbalance with SMOTE
Compare multiple Machine Learning models
Optimize model performance
Save the best model for deployment

📂 Dataset
Dataset: Credit Card Fraud Detection
Source: Kaggle
Rows: 284,807
Columns: 31
Target Variable: Class
Class	Meaning
0	Genuine Transaction
1	Fraudulent Transaction

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
SMOTE
Joblib

📊 Project Workflow
Data Loading
Data Cleaning
Exploratory Data Analysis
Feature Scaling
Train-Test Split
SMOTE
Model Training
Hyperparameter Tuning
Model Evaluation
Model Saving

🤖 Machine Learning Models
Logistic Regression
Decision Tree
Random Forest
XGBoost

📈 Final Results
Metric	Score
Best Model	Random Forest
Accuracy	99.94%
Precision	84.09%
Recall	77.89%
F1 Score	80.87%
ROC-AUC	98.24%

📁 Repository Structure
Credit-Card-Fraud-Detection
│
├── Credit_Card_Fraud_Detection.ipynb
├── requirements.txt
├── README.md
├── LICENSE

🚀 Future Improvements
Streamlit Web App
SHAP Explainability
FastAPI Integration
Real-Time Fraud Detection
Cloud Deployment

👩‍💻 Author

Abeera Haya

BS Information Technology

Machine Learning & AI Enthusiast
