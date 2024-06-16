# Credit_card_fraud_detection
Link for dataset is https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

This project aims to detect fraudulent credit card transactions using logistic regression. The dataset includes various features, such as v1, v2, ..., v28, along with time and amount, which indicate the transaction time and amount, respectively. The class column indicates the legitimacy of transactions, where 0 denotes genuine transactions and 1 denotes fraudulent ones.

Dataset Overview
Features (v1, v2, ..., v28): Anonymized attributes resulting from a PCA transformation.
Time: The elapsed time from the first transaction in the dataset.
Amount: The transaction amount.
Class: The target variable (0 for genuine transactions, 1 for fraudulent transactions).
Objective
To build a logistic regression model that accurately identifies fraudulent transactions.

Steps
Data Preprocessing:

Load the dataset.
Handle missing values if any.
Normalize/Standardize time and amount features.
Exploratory Data Analysis:

Analyze the distribution of genuine and fraudulent transactions.
Visualize relationships between features and the target variable.
Model Training:

Split the data into training and testing sets.
Train a logistic regression model on the training data.
Validate the model using the testing data.
Evaluation:

Evaluate model performance using metrics such as accuracy
