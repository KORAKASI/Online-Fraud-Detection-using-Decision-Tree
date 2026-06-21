# Online-Fraud-Detection-using-Decision-Tree

## Overview

Online financial fraud has become a significant challenge in the digital era, resulting in substantial monetary losses for businesses and individuals. Early detection of fraudulent transactions is essential to ensure secure online financial systems.

This project aims to develop a Machine Learning model capable of detecting fraudulent online transactions using the **Decision Tree Classifier** algorithm. The model analyzes transaction patterns and predicts whether a transaction is fraudulent or legitimate.

---

## Objective

The primary objective of this project is to build a robust classification model that identifies fraudulent transactions based on historical transaction data.

The developed model can assist financial institutions and online payment platforms in preventing fraud and minimizing financial losses.

---

## Dataset Information

The dataset used in this project contains financial transaction records collected from an online payment system. The primary objective of the dataset is to identify fraudulent transactions and distinguish them from legitimate transactions.

### Dataset Overview

- **Dataset Name:** Online Fraud Detection Dataset
- **File Name:** `onlinefraud.csv`
- **Problem Type:** Binary Classification
- **Target Variable:** `isFraud`

### Target Variable

| Variable | Description |
|----------|-------------|
| `isFraud` | Indicates whether a transaction is fraudulent (`1`) or legitimate (`0`) |

---

## Dataset Features

| Feature | Description |
|----------|-------------|
| `step` | Represents a unit of time in hours. Each step corresponds to one hour of real-world time. |
| `type` | Type of transaction performed (PAYMENT, TRANSFER, CASH_OUT, CASH_IN, DEBIT). |
| `amount` | Amount involved in the transaction. |
| `nameOrig` | Unique identifier of the customer initiating the transaction. |
| `oldbalanceOrg` | Initial balance of the sender before the transaction. |
| `newbalanceOrig` | Remaining balance of the sender after the transaction. |
| `nameDest` | Unique identifier of the transaction recipient. |
| `oldbalanceDest` | Initial balance of the recipient before the transaction. |
| `newbalanceDest` | Remaining balance of the recipient after the transaction. |
| `isFraud` | Indicates whether the transaction is fraudulent (`1`) or not (`0`). |
| `isFlaggedFraud` | Indicates whether the transaction was flagged as suspicious by the system. |

---

## Dataset Usage

This dataset is used for:

- Fraud detection analysis
- Exploratory Data Analysis (EDA)
- Feature engineering and preprocessing
- Building classification models
- Detecting fraudulent financial transactions
- Evaluating machine learning model performance
---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Plotly
- Scikit-learn

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Handling Missing Values
6. Feature Selection
7. Train-Test Split
8. Model Training using Decision Tree Classifier
9. Model Evaluation
10. Fraud Prediction

---

## Model Used

### Decision Tree Classifier

Decision Tree is a supervised machine learning algorithm used for classification and regression tasks. It creates a tree-like structure where each internal node represents a decision based on feature values.

The model recursively splits the dataset into subsets based on the feature that provides the highest information gain.

### Advantages

- Easy to interpret and visualize
- Handles both numerical and categorical data
- Requires minimal data preprocessing
- Captures non-linear relationships effectively
---
## Business Impact

A fraud detection system provides several benefits:

- Prevents financial losses
- Improves transaction security
- Reduces fraudulent activities
- Enhances customer trust
- Supports real-time fraud monitoring

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Classification problems in Machine Learning
- Data preprocessing and feature engineering
- Decision Tree implementation
- Fraud detection techniques
- Model evaluation using classification metrics
- End-to-end machine learning workflow

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ star on GitHub.
