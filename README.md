# Fraud detection using probability markov chain and stochastic models - Python
Markov Chain and Stochastic models - Machine learning models

This project focuses on detecting fraudulent financial transactions using a combination of stochastic modeling techniques and machine learning algorithms implemented in Python. The objective is to identify potentially fraudulent credit card transactions in a highly imbalanced dataset, where fraudulent events represent a small fraction of all transactions. The project uses a simulated transaction dataset sourced from Kaggle, designed to reflect realistic transaction behavior while preserving data privacy. Due to the rarity and dynamic nature of fraud, the problem is treated as both a binary classification task and an anomaly detection problem, allowing for a robust comparison of modeling approaches.

OBJECTIVES
To explore transaction-level patterns associated with fraudulent behavior
To handle severe class imbalance commonly present in fraud datasets
To apply supervised learning and stochastic/anomaly-based models
To evaluate model performance using metrics appropriate for rare-event detection

METHODOLOGY
1. Data Preprocessing
Data cleaning and feature selection
Removal of identifier variables to prevent data leakage
Feature scaling using standardization
Stratified train–test splitting to preserve class distribution

2. Class Imbalance Handling
Synthetic Minority Over-sampling Technique (SMOTE) to balance training data
Use of class-weighted models to reduce bias toward majority classes

3. Modeling Approaches
Logistic Regression (baseline supervised classifier)
Random Forest Classifier (non-linear ensemble method)
Isolation Forest (unsupervised anomaly detection model based on stochastic isolation principles)

Model performance is assessed through the following metrics
- Precision
- Recall
- F1-score
- ROC–AUC
- Precision–Recall AUC

