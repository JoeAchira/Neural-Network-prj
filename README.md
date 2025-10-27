# Neural-Network-project
Project using Neural Networks to model student dropout
Student Dropout Prediction using XGBoost
## Project Overview

This project predicts the likelihood of student dropout based on academic, demographic, and engagement data.
It was completed as part of my Data Science course focusing on handling imbalanced classification problems using advanced machine learning techniques.

The goal was to identify students at risk of dropping out early in the program, allowing institutions to take proactive support measures.

## Objectives

Build a predictive model to classify students as “Dropout” or “Completed.”

Address data imbalance (majority of students complete the course).

Compare model performance and tune hyperparameters for optimal results.

Evaluate results using ROC-AUC and other relevant metrics.

## Methods & Tools

Languages: Python

Libraries: XGBoost, scikit-learn, pandas, NumPy, matplotlib, seaborn

## Techniques:

Data preprocessing and feature scaling

Handling class imbalance with scale_pos_weight

Hyperparameter tuning (learning_rate, max_depth, n_estimators)

Stratified K-Fold cross-validation

Model evaluation using ROC-AUC, confusion matrix, and feature importance

## Model Development Steps

Data Exploration & Cleaning:
Identified missing values, outliers, and key correlations between variables such as attendance rate, GPA, and engagement.

Feature Engineering:
Encoded categorical features and normalised numerical ones.

Model Training:
Trained an XGBoost classifier with tuned parameters for optimal ROC-AUC performance.

Evaluation:
Used ROC-AUC, precision, recall, and confusion matrix to assess predictive strength.

Interpretation:
Analysed feature importance and identified main drivers of dropout risk.

## Results
Metric	Value
ROC-AUC	0.92
Precision	0.81
Recall	0.76
Accuracy	0.88

## Top predictors of dropout included:

- Attendance rate

- Average assessment score

- Time spent on the learning platform

- Early-term performance indicators

## Learning Outcomes

Strengthened understanding of imbalanced data handling and ROC-AUC optimisation.

Applied Stratified K-Fold validation to ensure robust performance estimates.

Improved feature engineering and hyperparameter tuning skills using real-world education data
