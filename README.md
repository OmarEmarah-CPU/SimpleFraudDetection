# SimpleFraudDetection
Fraud detection using XGBoost on highly imbalanced transaction data, with cross-validation, threshold , and evaluation metrics for minority-class detection.

# Fraud Detection with XGBoost

This project implements a fraud detection pipeline using XGBoost, designed to handle highly imbalanced transaction data. 
It includes:

- Data cleaning and feature selection
- Cross-validation for model evaluation
- Handling class imbalance using `scale_pos_weight`
- Model evaluation using precision, recall, F1-score, confusion matrix, and ROC-AUC
- Threshold tuning to optimize recall while controlling false positives

The goal is to build a model that reliably detects fraudulent transactions while minimizing false alarms.

