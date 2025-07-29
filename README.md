# Customer Churn Prediction using Stacked Ensemble Learning

This project predicts whether a customer will churn based on financial and demographic data using supervised machine learning techniques. It uses a stacked ensemble of XGBoost, Logistic Regression, and KNN for better accuracy and stability.

## Dataset
- Source: [Kaggle / Synthetic dataset]
- Records: 90,000+
- Features: 14 (e.g., credit score, age, balance, tenure, account activity)

## ML Pipeline
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training & Tuning
  - Models: XGBoost, Logistic Regression, KNN
  - Stacked Ensemble
  - Stratified 5-fold Cross-Validation
- Evaluation: Accuracy, F1-Score, ROC-AUC

## Results
- Accuracy: **85%**
- F1-Score: **0.65**
- ROC-AUC: **0.87**

## Tech Stack
`Python` `Scikit-learn` `XGBoost` `Pandas` `Matplotlib` `Seaborn`

## Key Highlights
- Stacked ensemble for improved performance
- Balanced class distribution
- Interpretability with feature correlation analysis
