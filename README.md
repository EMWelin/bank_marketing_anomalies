# bank_marketing_anomalies

# Anomaly Detection on Bank Marketing Data

Perform unsupervised anomaly detection on real-world bank marketing data using Support Vector Machine.  
This project is intended as a practical exercise in anomaly detection techniques using real-world data.


## Description

This project applies anomaly detection techniques on the [Bank Marketing dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing) from the UCI Machine Learning Repository.

Anomaly detection is usually used for unsupervised or semi-supervised learning. This dataset is fully labelled, which means supervised learning methods will likely outperform anomaly detection methods. Nonetheless, it remains an excellent dataset for practicing and benchmarking anomaly detection techniques.

## Dataset

- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- Size: Approximately 55,000 records
- Labels: 'yes' or 'no' indicating if the client subscribed to a term deposit
- Features: Mix of numerical and categorical attributes related to client demographics, contact, and campaign details

## Results

- Achieved an F1-score of **0.3335** on the anomaly (positive) class
- Overall F1-score: **0.80**

These results demonstrate the potential of anomaly detection approaches on labeled but imbalanced datasets.   
A higher overall F1-score of 0.83 with lower anomaly F1-score was achieved by choosing different hyperparameters.   
But,  optimising with respect to the anomaly class makes more sense as this class indicates potential customers.




