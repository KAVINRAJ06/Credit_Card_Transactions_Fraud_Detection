# Credit Card Fraud Detection

This project implements a credit card fraud detection model using a dataset containing information about credit card transactions. The goal is to classify transactions as fraudulent using logistic regression

## Features
- **Data Preprocessing**: The dataset is cleaned and transformed, including datetime processing to extract useful features.
- **Modeling**: A logistic regression model is used to classify transactions. The model is trained on a training dataset and evaluated on a test dataset.
- **Feature Scaling and Encoding**: Numerical features are standardized, while categorical features are one-hot encoded to prepare the data for the model.
- **Performance Evaluation**: The model achieved an accuracy of 99% on the test dataset, and a correlation heatmap for numeric features is generated to visualize relationships.

## Datasets
- **[fraudTrain.csv](https://www.kaggle.com/datasets/kartik2112/fraud-detection)**: The training dataset containing labeled transactions.
- **[fraudTest.csv](https://www.kaggle.com/datasets/kartik2112/fraud-detection)**: The testing dataset used to evaluate the model's performance.

## Visualization
A correlation heatmap is generated to understand the relationships between numeric features and fraudulent transactions.
