# Fraud Detection using Machine Learning

A machine learning project that detects fraudulent financial transactions using classification algorithms on a highly imbalanced dataset. The project covers the complete machine learning workflow, from data preprocessing and feature engineering to model evaluation and comparison.

## Project Overview

This project aims to identify fraudulent transactions by building and evaluating multiple machine learning models. Since fraud cases are rare, SMOTE (Synthetic Minority Oversampling Technique) was used to handle class imbalance and improve model performance.

## Dataset

- Dataset: Fraud Detection Dataset by Kartik2112
- Files Used:
  - `fraudTrain.csv`
  - `fraudTest.csv`

## Project Workflow

- Data Loading & Exploration
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- One-Hot & Frequency Encoding
- Feature Scaling
- Handling Class Imbalance using SMOTE
- Model Training & Evaluation
- Hyperparameter Tuning
- Model Comparison

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Extra Trees Classifier

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve

# Best Model

Random Forest achieved the best overall performance with the highest F1-Score and ROC-AUC, making it the most suitable model for this fraud detection task.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

