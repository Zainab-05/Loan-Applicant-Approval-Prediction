📌 Loan Applicant Approval Prediction
📁 Project Overview

This project focuses on analyzing and predicting loan approval outcomes based on applicant demographics, financial indicators, and credit history.
Using two structured Jupyter Notebooks, the workflow moves from data exploration and preprocessing to model development and performance evaluation.

The objective is to build a reliable model that helps identify which applicants are more likely to be approved, supporting credit risk decision-making.

📂 Dataset Description

The dataset contains records of past loan applicants, along with their personal, financial, and loan-related attributes.

Key Columns
Column	Description
Gender	Applicant gender
Married	Marital status
Dependents	Number of dependents
Education	Graduate / Not Graduate
Self_Employed	Work status
ApplicantIncome	Monthly income of the applicant
CoapplicantIncome	Monthly income of co-applicant
LoanAmount	Requested loan amount
Loan_Amount_Term	Loan duration (in months)
Credit_History	Credit repayment history (1 = good, 0 = bad)
Property_Area	Applicant’s location type
Loan_Status	Target variable (Y = Approved, N = Rejected)

The dataset is moderately clean but contains missing values that are handled during preprocessing.

📒 Notebook 1 — Credit Risk Analysis 

This notebook focuses on understanding the data and preparing it for modeling.

🔍 Steps Covered

Importing and inspecting the dataset
Handling missing values (mean/median for numeric, mode for categorical)
Visualizing income distribution, credit history patterns, loan amounts
Generating pairplots & correlation heatmaps
Encoding categorical variables
Outlier detection and basic feature scaling
Splitting data into training and test sets

🎯 Key Insights

Credit history is the strongest predictor of approval
Higher applicant income tends to correlate with higher approval
Urban applicants show slightly better approval ratios
Loan amount and loan term impact approval quality
The output of this notebook is a fully cleaned and transformed dataset ready for model training.

📘 Notebook 2 — Loan Application Prediction Model
This notebook focuses on training multiple models and evaluating which performs best for the approval prediction task.

🤖 Models Implemented
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
XGBoost

📊 Evaluation Metrics

Accuracy Score
Confusion Matrix
Classification Report (Precision, Recall, F1-score)
Feature Importance plots

🏆 Best Performing Model
The Random Forest model delivers the most stable and accurate predictions, achieving ~80–85% accuracy, depending on hyperparameters and preprocessed features.

🧠 What This Project Demonstrates
Ability to clean and preprocess real-world data
Understanding of credit risk–related variables
Comparing multiple ML models for classification
Identifying important drivers of loan approval
Structuring work clearly across notebooks for readability


Open the notebooks in order:

1 credit-risk-eda.ipynb
2 loan-applicant-prediction-model.ipynb

