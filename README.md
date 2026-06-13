# Fraud Detection System

## Project Overview

This project aims to detect fraudulent credit card transactions using Machine Learning. Fraud detection is an important application of data science in the banking and financial sector. The model analyzes transaction data and classifies transactions as either legitimate or fraudulent.

---

## Objective

The main objective of this project is to:

- Identify fraudulent transactions.
- Analyze transaction patterns.
- Build a Machine Learning model for fraud detection.
- Evaluate model performance using classification metrics.
- Visualize insights using graphs and dashboards.

---

## Dataset

Dataset: 
 The dataset used in this project is too large to be included in this repository.

You can download it from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

File used: creditcard.csv

Features:

- Time
- V1 to V28 (anonymized features)
- Amount
- Class

Target Variable:

- Class = 0 → Normal Transaction
- Class = 1 → Fraud Transaction

Dataset Size:

- Total Records: 284,807
- Total Features: 31

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Power BI
- GitHub

---

## Exploratory Data Analysis

The following visualizations were created:

### 1. Fraud vs Normal Transaction Distribution

Shows the distribution of fraudulent and non-fraudulent transactions.

### 2. Transaction Amount Distribution

Analyzes the distribution of transaction amounts.

### 3. Fraud vs Normal Transaction Amount Comparison

Compares transaction amounts between fraud and normal transactions.

### 4. Correlation Heatmap

Shows correlations between features.

### 5. Confusion Matrix

Evaluates model prediction performance.

---

## Machine Learning Model

Algorithm Used:

- Logistic Regression

Steps Performed:

1. Data Loading
2. Data Exploration
3. Feature Selection
4. Train-Test Split
5. Model Training
6. Prediction
7. Model Evaluation

---

## Model Performance

### Accuracy

99.94%

### Classification Report

Fraud Class Performance:

- Precision: 0.87
- Recall: 0.73
- F1-Score: 0.80

### Confusion Matrix

| Actual / Predicted | Normal | Fraud |
|-------------------|--------|--------|
| Normal | 56853 | 11 |
| Fraud | 26 | 72 |

---

## Project Structure

```text
Fraud-Detection-System/
│
├── data/
│   └── creditcard.csv
│
├── notebook/
│   └── fraud_detection.ipynb
│
├── images/
│   ├── fraud_distribution.png
│   ├── amount_distribution.png
│   ├── fraud_amount_comparison.png
│   ├── correlation_heatmap.png
│   └── confusion_matrix.png
│
├── model/
│   └── fraud_model.pkl
│
├── fraud_predictions.csv
│
└── README.md
```

---

## Results

- Successfully detected fraudulent transactions.
- Achieved high classification accuracy.
- Built a machine learning model using Logistic Regression.
- Generated visual insights through EDA.
- Created a dataset containing model predictions.

---

## Future Improvements

- Random Forest Classifier
- XGBoost Classifier
- Real-Time Fraud Detection
- Interactive Power BI Dashboard
- Model Deployment using Flask

---

## Author

Vishal Kumar

