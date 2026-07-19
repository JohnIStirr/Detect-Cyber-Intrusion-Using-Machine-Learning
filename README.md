# 🛡️ Network Intrusion Detection with Machine Learning

A machine learning project that builds and compares multiple classification models for detecting malicious network traffic. Using the **SIMARGL2021** dataset, the project explores data preprocessing, feature engineering, model training, and performance evaluation for intrusion detection.

---

## Overview

This project demonstrates an end-to-end machine learning workflow for network traffic classification. After exploring and preprocessing the dataset, multiple supervised learning models are trained to classify network traffic as benign or malicious and identify different attack types.

---

## Features

- Exploratory data analysis and visualization using Matplotlib
- Data preprocessing with Pandas and NumPy
- Feature scaling and categorical encoding
- Multi-class classification using scikit-learn
- Performance comparison across multiple machine learning models

---

## Models

The following classifiers were trained and evaluated:

- **Random Forest**
- **Decision Tree**
- **Gaussian Naive Bayes**

Models were compared using:

- Accuracy
- Precision
- Recall
- Training time

---

## Workflow

```text
SIMARGL2021 Dataset
        │
        ▼
Data Exploration
        │
        ▼
Preprocessing & Feature Engineering
        │
        ▼
Train/Test Split
        │
        ▼
Model Training
(Random Forest / Decision Tree / Naive Bayes)
        │
        ▼
Performance Evaluation
```

---

## Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## Key Concepts

- Supervised Machine Learning
- Classification
- Feature Engineering
- Data Preprocessing
- Model Evaluation
- Network Traffic Analysis

---

## Future Improvements

- Evaluate Gradient Boosting and XGBoost models
- Apply feature selection and dimensionality reduction
- Perform hyperparameter tuning with Grid Search
- Address class imbalance using sampling techniques
- Build a real-time inference pipeline for streaming network data
