📘 Customer Churn Prediction – Advanced Machine Learning Project

A complete, end-to-end machine learning project to predict customer churn using advanced preprocessing, model selection, hyperparameter tuning, evaluation, and explainability (SHAP).
This project is built using Python, Scikit-Learn, and SHAP and is structured for scalability and production-readiness.

🚀 Project Overview

Customer churn refers to when customers stop using a company’s service.
This project builds a predictive model that uses historical customer data to estimate the probability of churn.

You will learn:

Data cleaning & preprocessing

Encoding categorical variables

Train/validation/test splitting

Model training (Random Forest, XGBoost, LightGBM, etc.)

Hyperparameter tuning with GridSearchCV

Model evaluation (AUC, confusion matrix, classification report)

SHAP interpretability

Exporting predictions for Power BI dashboards

📂 Project Structure
customer-churn/
│
├── data/
│   ├── raw.csv
│   └── processed.csv
│
├── notebooks/
│   └── churn_model.ipynb
│
├── models/
│   └── best_model.pkl
│
├── reports/
│   ├── shap_summary.png
│   ├── feature_importance.csv
│   └── evaluation_metrics.txt
│
├── README.md
└── requirements.txt

🧠 Machine Learning Pipeline
1️⃣ Data Preprocessing

Identifying numeric & categorical features

Imputing missing values

Scaling numerical features

One-Hot encoding categorical features

Building a ColumnTransformer

2️⃣ Model Training

Models tested:

Random Forest

XGBoost (optional)

LightGBM (optional)

Gradient Boosting

Logistic Regression (baseline)

Hyperparameter tuning performed using:

GridSearchCV(cv=5, scoring="roc_auc")

3️⃣ Model Evaluation

Metrics used:

Accuracy

Precision, Recall, F1

ROC-AUC

Confusion Matrix

Classification Report

Visual outputs:

ROC curve

Confusion Matrix Heatmap

4️⃣ Explainability (SHAP)

We use SHAP to interpret:

Global feature importance

Per-customer explanations

Summary (beeswarm) plot

Waterfall plots

Outputs saved in /reports/.

📊 Key Results

Model: Random Forest (best after tuning)

ROC-AUC: ~0.85–0.92 (depends on dataset)

Top predictive features:

Tenure

MonthlyCharges

Contract type

Internet service

Payment method

SHAP confirms strong agreement with model insights.
