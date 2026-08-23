# Fraud Prediction in Financial Transactions

Compare the performance of differnet machine learning models on the detection of fraud in financial transactions.

Modelos comparados:
- MLP (Neural Network);
- Random Forest;
- Gradient Boosting; 
- Isolation Forest.

Metricas de comparação (afins):
- Accuracy;
- Precision;
- Recall;
- F1-Score;
- Matriz de confusão.

## About Dataset
This dataset contains 5 million synthetically generated financial transactions designed to simulate real-world behavior for fraud detection research and machine learning applications. Each transaction record includes fields such as:

- Transaction Details: ID, timestamp, sender/receiver accounts, amount, type (deposit, transfer, etc.)
- Behavioral Features: time since last transaction, spending deviation score, velocity score, geo-anomaly score
- Metadata: location, device used, payment channel, IP address, device hash
- Fraud Indicators: binary fraud label (is_fraud) and type of fraud (e.g., money laundering, account takeover)

The dataset follows realistic fraud patterns and behavioral anomalies, making it suitable for:
- Binary and multiclass classification models
- Fraud detection systems
- Time-series anomaly detection
- Feature engineering and model explainability

Source: Kaggle.