# Credit Card Fraud Detection
 
This repository contains a Jupyter Notebook for detecting fraudulent transactions in credit card datasets using machine learning techniques.

## Overview
  
Credit card fraud is a significant issue in the financial industry, and early detection of fraudulent transactions can help mitigate financial losses. This notebook presents a solution for identifying fraudulent transactions using various machine learning models and techniques. The goal is to accurately distinguish between legitimate and fraudulent transactions based on transaction features.

## Dataset

The dataset used for this project includes anonymized credit card transaction data with a mix of legitimate and fraudulent transactions. Each transaction has a set of features that provide insights into the nature of the transaction while protecting sensitive information.

## Features

The features in this dataset are numerical and represent transformations or results of principal component analysis (PCA) to protect privacy. The target variable indicates whether a transaction is fraudulent (`1`) or legitimate (`0`).

## Project Structure

- **Data Exploration**  
  - Perform initial exploration to understand the distribution of data.
  - Identify any imbalances between classes (fraudulent and non-fraudulent transactions).

- **Data Preprocessing**  
  - Scale features to improve model performance.
  - Handle class imbalance using techniques like SMOTE (Synthetic Minority Over-sampling Technique).

- **Model Training**  
  - Train several machine learning models, including:
    - Logistic Regression
    - Decision Tree
    - Random Forest
    - Gradient Boosting
    - Support Vector Machine

- **Evaluation**  
  - Evaluate models based on metrics such as:
    - Accuracy
    - Precision
    - Recall
    - F1-score
  - Emphasize metrics that address class imbalance, which are crucial for fraud detection.

## Requirements

To run the notebook, install the following packages:

```bash
pip install numpy pandas scikit-learn imbalanced-learn matplotlib seaborn
