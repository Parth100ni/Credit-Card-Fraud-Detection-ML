# Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using Machine Learning classification techniques.

## Problem Statement
Credit card fraud is a major issue in financial systems. The goal of this project is to build a model that can accurately identify fraudulent transactions while minimizing false positives.

## Dataset
- Source: Kaggle (Credit Card Fraud Detection Dataset)
- Total records: 284,807 transactions
- Highly imbalanced dataset
- Target variable: Class (0 = Genuine, 1 = Fraud)

## Methodology
- Data preprocessing and analysis
- Train-test split with stratification
- Handling class imbalance using SMOTE
- Feature scaling using StandardScaler
- Model training using Logistic Regression
- Model evaluation using classification metrics

## Model Used
- Logistic Regression
- SMOTE for imbalance handling

## Results
- Accuracy: ~99%
- ROC-AUC Score: ~0.97
- High recall for fraud class

## Evaluation Metrics
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Google Colab

## Files in this Repository
- Jupyter Notebook (.ipynb)
- Project Report (.pdf)

This project was developed as part of the **AI & ML with Python** program.
