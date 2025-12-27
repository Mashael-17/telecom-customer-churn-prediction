# telecom-customer-churn-prediction
Predicting telecom customer churn using machine learning

Telecom Customer Churn Prediction
Project Summary

This project predicts customer churn for a telecommunications company using supervised machine learning. The objective is to identify key churn drivers and build a model that can support data-driven retention strategies.

## Data

7,043 customers, 21 features

Customer demographics, services, contract details, and billing information

Target: Churn (Yes / No)

Churn rate: ~26.6% (imbalanced)

## Approach

Data cleaning and preprocessing

Exploratory data analysis to identify churn patterns

Feature encoding and transformation

Model training and comparison:

Logistic Regression

Decision Tree

Hyperparameter tuning using GridSearchCV

Evaluation using Accuracy, Precision, Recall, F1-score, and ROC-AUC

## Results

Best model: Tuned Decision Tree Classifier

Accuracy: 78.7%

Model performs well overall, with lower recall for churned customers due to class imbalance

## Key Insights

Contract type is the strongest predictor of churn

Customers on short-term (month-to-month) contracts are more likely to churn

Tenure and total charges are also significant drivers

Optional services (e.g., streaming, device protection) have minimal impact

## Business Impact

These findings can help telecom companies:

Identify high-risk customers early

Prioritize retention efforts for short-term contracts

Improve customer lifetime value through targeted interventions

## Note

This project was developed as part of my Master of Data Science program, within the
Advanced Data Mining course.
