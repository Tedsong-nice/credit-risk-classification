credit-risk-classification

Overview

This project aims to predict the risk status of loans ("Healthy Loan" or "High-Risk Loan") using a logistic regression model. By analyzing the given dataset, the model classifies loans based on their features, providing insights into loan risk.
Key Steps

Data Loading and Inspection

Load the dataset from a CSV file.

Inspect the structure, missing values, and distribution of the target variable.

Data Preprocessing

Separate the data into features (X) and labels (y).

Standardize the feature data to ensure uniform scaling.

Data Splitting

Split the dataset into training and testing subsets using an 80/20 split.

Use the training set to train the model and the testing set to evaluate it.

Model Training

Build a logistic regression model using scikit-learn.

Train the model on the training data.

Model Prediction

Predict loan statuses for the testing data.

Model Evaluation

Evaluate model performance using metrics such as:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

