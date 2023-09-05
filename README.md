# Financial Fraud Mitigation Project

Dataset: https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection

Overview

Transaction fraud can result in substantial financial losses for individuals, businesses, and financial institutions. By successfully detecting and preventing fraudulent transactions, your project directly contributes to minimizing these losses. A robust fraud detection system helps maintain and enhance customer trust. When customers feel their transactions are secure, they are more likely to continue using a financial service, leading to customer retention and growth. This project aims to build a robust transaction fraud detection model using the XGBoost algorithm. The model is designed to identify fraudulent transactions within a dataset by leveraging various data preprocessing and feature selection techniques.

Feature Engineering:
A significant effort has been invested in feature engineering. Creative feature engineering involves crafting new features from the existing data to provide the model with more relevant information and improve its predictive capabilities.

Model Pipeline:
The model consists of several key components organized into a pipeline:

Data Preprocessing:

Step 1: Categorical Feature Transformation
One-Hot Encoding for categorical features.

Step 2: Resampling
SMOTEENN resampling method to address class imbalance.

Step 3: Numerical Feature Scaling
StandardScaler to scale numerical features.

Feature Selection:

Step 4: SelectKBest
Feature selection using the SelectKBest method with the F-statistic (f_classif) scoring function to select the top features.

Classification Model:

Step 5: XGBoost Classifier
XGBoost Classifier with specified hyperparameters for binary classification.

Step 6: Hyperparameter Tuning
A random search is conducted to optimize the hyperparameters of the XGBoost Classifier. 

Evaluation Metric:
The model performance is assessed using the ROC AUC (Receiver Operating Characteristic Area Under the Curve) scoring metric.

Usage:
This model can be used to detect fraudulent transactions by inputting transaction data into the pipeline for preprocessing, feature selection, and classification.

⭐️ If you find this project useful or interesting, please consider giving it a star! ⭐️

# Thank You.
