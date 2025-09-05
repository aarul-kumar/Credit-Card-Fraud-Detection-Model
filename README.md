Credit-Card-Fraud-Detection-Model

Dataset used: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

This dataset, used for training machine learning models to detect fraudulent credit card transactions, contains 31 features and a class label. The features include Time, representing the elapsed seconds from the first transaction, and Amount, which is the transaction amount in USD. There are also 28 anonymized features, labeled V1 to V28, which are the result of a Principal Component Analysis (PCA) transformation of the original data. The final feature, Class, is a binary label that indicates whether a transaction is fraudulent (1) or not (0).

Key Features-
Time: The elapsed time in seconds since the very first transaction in the dataset.
V1-V28: Anonymized features derived from PCA, a technique that reduces the dimensionality of the original data while retaining most of its variance. These features capture various transaction details like location and type.
Amount: The monetary value of the transaction in US dollars.
Class: The target variable, indicating fraud (1) or a legitimate transaction (0).
