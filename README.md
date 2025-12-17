# Fraud Detection using Machine Learning

## 📌 Overview
This project implements a machine learning–based fraud detection system to identify fraudulent financial transactions at scale. The primary focus is on handling extreme class imbalance and optimizing precision to minimize false positives in real-world fraud detection scenarios.

## 🎯 Problem Statement
In financial transaction datasets, fraudulent cases are extremely rare compared to legitimate transactions. Traditional accuracy-based evaluation can be misleading in such scenarios. This project focuses on:
- Precision-driven evaluation
- Robust model comparison
- Reducing false positives in fraud detection systems

## 📊 Dataset
- Total transactions: 76,351,452
- Features include:
  - Transaction type
  - Transaction amount
  - Origin and destination account balances
- Target variable: Fraud / Non-Fraud
- Dataset source: Public dataset
- **Note:** The full dataset is not included in this repository due to size constraints.

## ⚙️ Methodology
1. Data cleaning and preprocessing
2. Feature selection and transformation
3. Handling severe class imbalance
4. Training and evaluating multiple machine learning models
5. Selecting the best model using precision, recall, and ROC-AUC

## 🤖 Models Evaluated
- Logistic Regression
- Random Forest
- AdaBoost
- Bagging Classifier

## 🏆 Results & Insights
- Logistic Regression demonstrated very low precision (~0.02), making it unsuitable for fraud detection
- Ensemble models significantly outperformed linear models
- Best-performing models achieved:
  - Precision ≈ 0.997
  - Recall ≈ 0.997
  - ROC-AUC ≥ 0.998
- Ensemble methods effectively captured complex fraud patterns

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook


