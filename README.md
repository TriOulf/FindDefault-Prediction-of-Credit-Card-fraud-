# FindDefault-Prediction-of-Credit-Card-fraud-

This project involves building a machine learning model to detect fraudulent credit card transactions using the creditcard.csv dataset. The dataset contains highly imbalanced data, and the goal is to predict fraudulent transactions accurately. The solution includes preprocessing, model training, evaluation, and deployment via a Flask API, packaged in a Docker container.

Table of Contents
Problem Statement
Dataset
Solution Overview
Technologies Used
Setup and Usage
Endpoints
Future Work
Contributing
Problem Statement
Credit card fraud detection is a critical issue for financial institutions. Fraudulent transactions cause significant financial and reputational damage. This project aims to:

Predict whether a transaction is fraudulent or not.
Handle the class imbalance using techniques like SMOTE.
Provide a deployed API for real-time predictions.
Dataset
The dataset contains credit card transactions made by European cardholders in September 2013. Key details:

Transactions: 284,807
Fraudulent Transactions: 492 (0.172%)
Features: 30 anonymized columns + Time and Amount.
Solution Overview
Steps
Exploratory Data Analysis (EDA): Understand data distribution and relationships.
Preprocessing: Handle missing values, outliers, and standardize Amount and Time.
Balancing the Dataset: Use SMOTE to address class imbalance.
Model Training: Train a Random Forest model to classify transactions.
Evaluation: Use metrics like RO
