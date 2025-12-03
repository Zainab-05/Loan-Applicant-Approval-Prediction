📌 Loan Applicant Approval Prediction
📁 Project Overview

This project analyzes and predicts loan approval outcomes using applicant demographics, financial indicators, and credit history.
Using two structured Jupyter Notebooks, the workflow moves from data exploration & preprocessing to model development and performance evaluation.

The objective is to build a reliable prediction model that supports credit risk–based decision-making.

📂 Dataset Description

The dataset includes historical loan applicants with demographic, financial, and loan-related attributes.

The dataset contains some missing values that are cleaned during preprocessing.

📒 Notebook 1 — Credit Risk Analysis

File: credit-risk-eda.ipynb

This notebook performs detailed exploratory data analysis and prepares the dataset for model building.

🔍 Steps Covered

Importing and inspecting the dataset

Handling missing values (numeric + categorical)

Visualizing income distributions, credit history trends, loan amounts

Generating pairplots and correlation heatmaps

Encoding categorical variables

Detecting outliers

Basic feature scaling

Splitting data into training and test sets

🎯 Key Insights

Credit history is the strongest driver of approval

Higher applicant income increases approval likelihood

Urban applicants show slightly higher approval ratios

Loan amount and term influence loan approval quality

Output → A fully cleaned and transformed dataset ready for modeling.

📘 Notebook 2 — Loan Application Prediction Model

File: loan-applicant-prediction-model.ipynb

This notebook builds and evaluates multiple machine learning models to predict loan approval.

🤖 Models Implemented

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

XGBoost

📊 Evaluation Metrics

Accuracy Score

Confusion Matrix

Precision, Recall, F1-Score

Feature Importance Visualization

🏆 Best Performing Model

The Random Forest Classifier delivers the most stable performance with an accuracy of ~80–85%, depending on parameter tuning and processed features.

🧠 What This Project Demonstrates

Ability to clean and preprocess real-world datasets

Understanding of credit-risk-related variables

Comparing multiple classification models

Identifying top drivers influencing approval decisions

Structuring work across separate notebooks for clarity and reproducibility

▶️ How to Use This Repository

Open the notebooks in the following order:

credit-risk-eda.ipynb

loan-applicant-prediction-model.ipynb


