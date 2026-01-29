# AI-Powered Customer Churn Prediction

## Problem Statement
Customer churn is a major challenge in the telecom industry. This project aims to
predict customer churn and identify key drivers to help businesses take proactive
retention actions.

## Dataset
- Telecom customer churn dataset
- Features include usage behavior, service plans, customer service calls, and tenure
- Target variable: Churn (Yes/No)

## Approach
1. Performed Exploratory Data Analysis (EDA) to identify churn patterns
2. Engineered behavioral features such as total usage and service-call flags
3. Built a robust ML pipeline with imputation and scaling
4. Trained Logistic Regression and Random Forest models
5. Used SHAP for model explainability
6. Translated predictions into actionable business insights

## Results
- Random Forest achieved better recall and ROC-AUC
- Customer service calls and international plan were top churn drivers

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- SHAP
- Matplotlib, Seaborn

## Business Impact
The model helps identify high-risk customers early, enabling targeted retention
strategies and reducing revenue loss.
