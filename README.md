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
