# Customer Churn Prediction

A machine learning project developed for **bKash Presents NSUCEC Cybernauts Datathon 2026**.

This project explores customer churn prediction using machine learning, with an emphasis on exploratory data analysis, feature engineering, imbalanced classification, model evaluation, and model interpretability.

## Event

- **Event:** bKash Presents NSUCEC Cybernauts Datathon 2026
- **Project:** Customer Churn Prediction

## Overview

Customer churn is a challenge for businesses because losing existing customers can reduce revenue and increase customer acquisition costs.

The goal of this project is to identify customers who are likely to churn by exploring customer data and developing predictive machine learning models.

## Objectives

- Perform exploratory data analysis (EDA).
- Engineer meaningful predictive features.
- Prepare data for machine learning.
- Investigate approaches for handling class imbalance.
- Compare classification models using appropriate evaluation metrics.
- Interpret model predictions and feature contributions.

## Tech Stack

- **Language:** Python
- **Data Processing:** Dask, NumPy
- **Visualization:** Matplotlib
- **Machine Learning:** Scikit-learn, XGBoost, LightGBM
- **Model Interpretability:** SHAP
- **Environment:** Kaggle Notebooks

*Update this list to match the libraries and tools actually used in your implementation.*

## Machine Learning Workflow

### 1. Exploratory Data Analysis

- Examine the dataset structure, feature distributions, and missing values.
- Analyze the target variable and investigate class imbalance.
- Explore relationships between customer features and churn.

### 2. Data Preprocessing and Feature Engineering

- Clean and transform features as needed.
- Prepare numerical and categorical features for modeling.
- Engineer useful features from available customer and transactional data.
- Avoid data leakage when splitting data and fitting preprocessing steps.

### 3. Handling Class Imbalance

When churn cases are less common than retained customers, a model may favor the majority class. Potential approaches include:

- Class weighting
- Random undersampling
- SMOTE oversampling

The selected approach should be evaluated on validation data. Apply resampling only to the training data.

### 4. Model Development

Models considered for comparison include:

| Model | Purpose |
|---|---|
| Logistic Regression | Establish an interpretable baseline |
| Random Forest | Capture nonlinear patterns and feature interactions |
| XGBoost | Explore gradient-boosted decision trees |
| LightGBM | Explore efficient gradient boosting |

*Retain only the models actually implemented in the project.*

### 5. Model Evaluation

Accuracy alone can be misleading when the target classes are imbalanced. Useful metrics include:

- **Precision:** The proportion of predicted churn cases that are actual churn cases.
- **Recall:** The proportion of actual churn cases identified by the model.
- **F1-score:** The harmonic mean of precision and recall.
- **ROC-AUC:** Measures how well the model separates the classes across thresholds.
- **PR-AUC:** Evaluates precision and recall across thresholds, especially useful for an underrepresented positive class.

The most suitable model depends on the validation results and the relative cost of missed churn cases and false alarms.

### 6. Model Interpretability

SHAP (SHapley Additive exPlanations) can be used to examine how individual features contribute to model predictions and identify factors associated with churn.

*Include this section only if SHAP or another interpretability method was actually used.*

## Results

Add your verified results here after evaluating the models.

| Model | Precision | Recall | F1-score | ROC-AUC | PR-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | — | — | — | — | — |
| Random Forest | — | — | — | — | — |
| XGBoost | — | — | — | — | — |
| LightGBM | — | — | — | — | — |

Replace the dashes with measured results and remove rows for models that were not evaluated. Do not report unverified metrics.

## Key Learnings

- Understanding class imbalance in classification tasks.
- Comparing machine learning models using suitable metrics.
- Exploring feature engineering for predictive modeling.
- Evaluating model performance beyond accuracy.
- Interpreting model predictions, where applicable.

## Future Improvements

- Perform systematic hyperparameter tuning.
- Optimize the prediction threshold based on business requirements.
- Evaluate generalization on unseen data.
- Build a reproducible prediction pipeline.
- Explore deployment through an API or dashboard.

## Project Status

This project was developed in the context of **bKash Presents NSUCEC Cybernauts Datathon 2026**.


