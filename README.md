# Spam Detection using Logistic Regression

## Overview

A binary classification project using logistic regression to detect spam emails based on the Spambase dataset. The project involves preprocessing, feature selection, model training, evaluation, and visualization.

## Dataset

- **Name:** Spambase Dataset  
- **Shape:** (4601, 58)  
- **Source:** UCI Machine Learning Repository

## Libraries Used

- pandas  
- seaborn  
- matplotlib.pyplot  
- sklearn:
  - linear_model: `LogisticRegression`
  - model_selection: `train_test_split`
  - metrics: `confusion_matrix`, `ConfusionMatrixDisplay`, `classification_report`, `roc_curve`, `auc`, `RocCurveDisplay`

## Workflow Summary

- Correlation-based feature selection (reduced features from 58 to 43)
- Features scaled using `StandardScaler`
- Model trained using logistic regression
- Evaluated using classification report and ROC-AUC curve

## Model Evaluation

- **Accuracy:** 92%
- **AUC Score:** 0.97

## How to Run

1. Clone the repository  
2. Install required libraries (`pip install -r requirements.txt`)  
3. Run the notebook or script to train and evaluate the model  

