# Breast Cancer Prediction using Logistic Regression

## Overview
This project implements a Logistic Regression model to classify tumors as malignant or benign based on features extracted from breast cancer cell nuclei. It builds and evaluates a binary classification model using Logistic Regression on the Breast Cancer Wisconsin dataset.

## Dataset

Source: Breast Cancer Wisconsin Dataset from Kaggle

Target Variable: Diagnosis (M = Malignant, B = Benign)

Features: 30 numerical attributes (radius, texture, perimeter, area, etc)

## Steps Covered

1. Imported necessary libraries.
2. Loaded and preprocessed the dataset (dropped ID column, encoded target labels, etc).
3. Standardized the features using StandardScaler.
4. Split the dataset into training and testing sets (80-20 split).
5. Built a Logistic Regression model using scikit-learn.
6. Evaluated the model using: Confusion Matrix, Precision, Recall, ROC-AUC Score, ROC Curve visualization.
7. Explained and visualized the sigmoid curve used by Logistic Regression.
8. Tuned the classification threshold and analyzed how it affects model performance.

## Evaluation Metrics

| Metric      | Score |
|-------------|-------|
| Precision   | 0.9761  |
| Recall      | 0.9534  |
| ROC-AUC     | 0.9973  |

## Important Notes

Sigmoid Function: Converts linear output to probability between 0 and 1, forming the basis of logistic regression.

Threshold Tuning: Lowering the threshold increases recall but may reduce precision, and vice versa.

ROC Curve: Ideal models have curves that hug the top-left corner; the area under the curve (AUC) closer to 1.0 indicates better performance.
