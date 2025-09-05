Credit-Card-Fraud-Detection-Model

Dataset used: https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa1F5elhGNWxVVUowamJTZFh1anVqOWpMQW1UZ3xBQ3Jtc0tuU0p5YmVZOUN4RldmazA5Y01OSTdwOFlJODctM3FiUW5tZUY2aTZFZzRxRUNHWWNHODdjLTVFblFyODdHS0pXYm1ITnRISXZmaXl4NlRpalNlbGVEcW4wSHhxZmxjd2N2Zl9tNEJ3M0l0TEM3OEdsaw&q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fmlg-ulb%2Fcreditcardfraud&v=239TaYSQI-s

This is a dataset containing credit card transactions with 31 features and a class label. The features represent various aspects of the transaction, and the class label indicates whether the transaction was fraudulent (class 1) or not (class 0).

The first feature is "Time", which represents the number of seconds elapsed between the transaction and the first transaction in the dataset. The next 28 features, V1 to V28, are anonymized variables resulting from a principal component analysis (PCA) transformation of the original features. They represent different aspects of the transaction, such as the amount, location, and type of transaction.

The second last feature is "Amount", which represents the transaction amount in USD. The last feature is the "Class" label, which indicates whether the transaction is fraudulent (class 1) or not (class 0).

Overall, this dataset is used to train machine learning models to detect fraudulent transactions in real-time. The features are used to train the model to learn patterns in the data, which can then be used to detect fraudulent transactions in future transactions.
