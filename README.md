# Proactive Fraud Detection: End-to-End Modeling, Analysis & Action Plan

This project demonstrates an **end-to-end fraud detection workflow** on a large transactions dataset (~6.36M rows). It covers data cleaning, exploratory analysis, feature engineering, model building, and evaluation.

## Project Overview
- **Dataset**: Transactions with user accounts, balances, transaction type, and fraud labels.
- [Dataset Source](https://drive.usercontent.google.com/download?id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV&export=download&authuser=0)
- [Data Dictionary](https://github.com/narpat78/Proactive-Fraud-Detection/blob/main/Data%20Dictionary.txt)
- **Workflow**:
  1. Data cleaning (duplicates, missing values, outliers, multicollinearity)
  2. Exploratory Data Analysis (EDA) and visualization
  3. Feature engineering for balance consistency and behavioral features
  4. Dataset preparation and splitting
  5. Modeling using Logistic Regression and Random Forest with imbalance handling
  6. Evaluation with accuracy, confusion matrix, and classification report
  7. Action plan with prevention strategies and monitoring recommendations

## Tech Stack
- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Outcomes
- Identified patterns in fraudulent transactions
- Built baseline models to classify fraud vs. non-fraud
- Recommended strategies for proactive fraud prevention
