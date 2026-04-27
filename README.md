# Credit-Card-Fraud-Detection
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to build a model that can accurately identify fraud cases while minimizing false positives, which is critical in real-world financial systems.

# Dataset
The dataset used is the Credit Card Fraud Detection dataset (commonly from Kaggle)
Contains anonymized features (V1–V28), Time, Amount, and Class
Class distribution is highly imbalanced:
Legitimate transactions ≫ Fraud transactions

# Evaluation Metrics

Since the dataset is imbalanced, accuracy alone is not sufficient. The following metrics are used:
Accuracy   : 93.4%
Precision  : 90.8%
Recall     : 95.6%      
F1-Score   : 93.1%

# Results
1.Achieved high recall for fraud detection
2.Balanced precision and recall using tuning
3.Model effectively detects rare fraud cases

# Future Improvements
->Use Deep Learning models (ANN, LSTM)
->Deploy using Flask / FastAPI
->Real-time fraud detection system
->Feature engineering for better accuracy
