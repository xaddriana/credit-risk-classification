# credit-risk-classification
Credit Risk Classification

This project involves the development and evaluation of a machine learning model for credit risk classification. The goal is to build a model that can identify the creditworthiness of borrowers based on historical lending activity data from a peer-to-peer lending services company.

Logistic Regression Model:
Original Model: A logistic regression model is trained using the original data. The model is then evaluated using a confusion matrix and a classification report.
Resampled Model: To address class imbalance, the training data is oversampled using the RandomOverSampler from the imbalanced-learn library. A logistic regression model is trained on the resampled data, and its performance is evaluated.

The logistic regression model demonstrates high performance in credit risk classification. Both models achieve high accuracy, with the resampled model showing improved performance for high-risk loans. 
