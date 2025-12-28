# Colorectal Cancer Survival Prediction Using Ensemble Machine Learning

## Overview
This project focuses on predicting 5-year survival outcomes of colorectal cancer patients using ensemble machine learning models and survival analysis techniques. It also demonstrates clinically actionable risk stratification.

## Objective
- Predict 5-year survival in colorectal cancer patients
- Compare ensemble ML models with Cox Proportional Hazards model
- Stratify patients into high-risk and low-risk groups for prognosis

## Dataset
- Clinical dataset of 929 colorectal cancer patients
- Variables include age, tumor extent, node involvement, surgery status, and follow-up time
- Public benchmark dataset used for survival analysis

## Methodology
- Data preprocessing and feature engineering
- Models used:
  - Random Forest
  - XGBoost
  - Gradient Boosting
- Performance evaluation using AUC
- Comparison with Cox Proportional Hazards model
- Kaplan–Meier survival analysis for risk stratification

## Results
- Random Forest achieved the best performance with an AUC of 0.864
- Clear separation between high-risk and low-risk patient groups
- Low-risk group showed significantly higher median survival compared to high-risk group

## Tools & Technologies
Python, Pandas, NumPy, Scikit-learn, XGBoost, Survival Analysis, Kaplan–Meier

## Academic Note
This is an academic research project completed as part of the MSc Business Statistics program at VIT Vellore.

