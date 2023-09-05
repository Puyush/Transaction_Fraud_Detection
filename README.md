# Financial Fraud Mitigation Project

Overview

This project aims to build a robust transaction fraud detection model using the XGBoost algorithm. The model is designed to identify fraudulent transactions within a dataset by leveraging various data preprocessing and feature selection techniques.

Model Pipeline
The model consists of several key components organized into a pipeline:

Data Preprocessing:

Step 1: Categorical Feature Transformation
One-Hot Encoding for categorical features.

Step 2: Resampling
SMOTEENN resampling method to address class imbalance.

Step 3: Numerical Feature Scaling
StandardScaler to scale numerical features.
