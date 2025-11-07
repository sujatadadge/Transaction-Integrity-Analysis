# 💳 Transaction Integrity Analysis — Financial Data Analytics using Python (Pandas & NumPy)

## 📊 Project Overview
This project explores **transaction integrity** using the **Credit Card Fraud Detection Dataset** from Kaggle.  
It focuses on understanding financial patterns, detecting anomalies, and performing deep **Exploratory Data Analysis (EDA)** with **Pandas** and **NumPy**.

---

## 🎯 Objectives
- Analyze and clean large-scale credit card transaction data  
- Use **NumPy** for statistical and numerical analysis  
- Perform **EDA** to understand fraud patterns  
- Derive insights on data imbalance and transaction anomalies  

---

## 🧰 Tools & Libraries
- **Python 3**
- **Pandas**
- **NumPy**
- (Optional: Google Colab / Jupyter Notebook)

---

## 📂 Dataset Information
**Dataset:** [Credit Card Fraud Detection Dataset – Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
**Transactions:** 284,807  
**Fraudulent Cases:** 492 (0.17%)  

This dataset represents highly imbalanced real-world banking data.

---

## 🧩 Project Workflow

### 1️⃣ Data Import
```python
import pandas as pd
import numpy as np

df = pd.read_csv('creditcard.csv')
df.head()
2️⃣ Data Cleaning

Handle missing values and duplicates

Rename columns (if necessary)

Normalize and understand distributions

3️⃣ Statistical Analysis with NumPy

Compute mean, median, variance, and standard deviation

Compare fraud vs non-fraud transactions

Detect anomalies using threshold-based methods

4️⃣ Exploratory Data Analysis (EDA)

Correlation between features and target class

Fraud rate vs transaction amount and time

Statistical difference between fraud and genuine transactions

📈 Key Findings

Only 0.17% of transactions are fraudulent

Fraud transactions often involve smaller average amounts

PCA components such as V14, V17, and V12 show strong fraud correlation

Fraud tends to occur during specific time periods

🧮 Concepts Applied

Data Cleaning and Filtering

Descriptive Statistics

Outlier Detection

Correlation Analysis

Data Imbalance Handling

💾 How to Run

Upload your creditcard.csv file to Google Colab

Run:

import pandas as pd, numpy as np
df = pd.read_csv('creditcard.csv')


Continue with EDA and statistical analysis steps

💡 Future Enhancements

Implement ML models (Logistic Regression, Random Forest)

Handle imbalance using SMOTE or undersampling

Visualize insights with Matplotlib or Seaborn

✨ Author

Sujata Dadge
📊 Aspiring Data Analyst | Financial Data Enthusiast
🔗 LinkedIn Profile

🌐 Kaggle Profile

💬 Summary

“Transaction Integrity Analysis” focuses on understanding and maintaining trust in financial systems through analytical methods.
By using Pandas and NumPy, this project reveals patterns and insights that help identify fraudulent behavior in real-world credit card transactions.


---

