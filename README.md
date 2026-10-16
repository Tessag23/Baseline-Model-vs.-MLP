# Heart Failure Prediction: Linear Model vs. MLP

Tech Stack: Python, pandas, NumPy, scikit-learn

- Developed a binary classification pipeline to predict heart-failure outcomes using patient data.
- Implemented and compared a baseline logistic regression model and a **Multi-Layer Perceptron (MLP) from scratch**, applying gradient descent for model optimization.
- Built a preprocessing pipeline incorporating missing-value imputation, feature standardization, and categorical encoding, fitting transformations on training data to prevent data leakage.
- Compared model performance on held-out test data using Accuracy, Precision, Recall, F1-score, analyzing predictive performance and model trade-offs.

## Problem Type
Binary Classification 

## Problem statement
This project aims to predict whether a patient has heart disease based on various medical and demographic attributes such as age, sex, chest pain type, blood pressure, cholesterol level, and maximum heart rate. Early prediction of heart disease is important because it can assist healthcare professionals in identifying high-risk patients and making timely treatment decisions. This is a binary classification problem where the target variable indicates the presence or absence of heart disease.

## Primary evaluation metric
recall

## Metric justification
Recall is selected as the primary evaluation metric because in medical diagnosis, failing to identify a patient who actually has heart disease (false negative) can have serious health consequences. A false positive may lead to additional testing, but a false negative could delay treatment and increase the risk to the patient. Therefore, maximizing recall is important to ensure that as many patients with heart disease as possible are correctly identified.