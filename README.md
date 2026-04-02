# 💳 Credit Card Fraud Detection System

## 📌 Project Overview
This project is a Machine Learning-based solution designed to detect fraudulent credit card transactions. Using a highly imbalanced dataset, I implemented data preprocessing and classification algorithms to accurately identify suspicious activities while minimizing false alarms.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **ML Model:** Random Forest Classifier
* **Visualization:** Power BI

## 📂 Dataset Information
The dataset used is the "Credit Card Fraud Detection" dataset from Kaggle.
* **Full Dataset:** The original `creditcard.csv` (143MB) is not uploaded due to GitHub's file size limits. 
* **Download Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* **Sample Data:** I have included `sample_creditcard.csv` (a smaller version) so the code can be tested immediately.

## 📊 Business Insights (Power BI)
Since the `.pbix` file is too large for GitHub, I have exported the full analysis as a PDF.
* **View Report:** Open `Fraud_Dashboard_Report.pdf` in this repository to see the transaction trends, fraud distribution, and KPI cards.

## 🚀 How to Run
1. Clone this repository or download the ZIP.
2. Install dependencies: `pip install pandas scikit-learn matplotlib seaborn`.
3. Open `fraud_detection.ipynb` in Jupyter Notebook.
4. Ensure `sample_creditcard.csv` is in the same folder and run all cells.

## 📈 Results
* **Model Accuracy:** ~95% on balanced test data.
* **Key Finding:** Features V14 and V17 showed the highest correlation with fraudulent behavior.

