# 🚨 Accredian Project Using Machine Learning

## 📌 Project Overview
This project focuses on building an end-to-end **fraud detection system** for a financial company using machine learning.  
The goal is to accurately identify fraudulent transactions and derive **actionable business insights** to help prevent fraud.

The solution follows a complete ML lifecycle:
- Data understanding and cleaning
- Exploratory Data Analysis (EDA)
- Feature selection
- Model building and evaluation
- Business interpretation and fraud prevention strategies

---

## 📂 Dataset Information
- **Source:** Provided as part of an industry case study
- **Rows:** ~6.3 million transactions
- **Columns:** 10
- **Target Variable:** `isFraud` (1 = Fraud, 0 = Non-Fraud)
- **Nature:** Highly imbalanced dataset (<1% fraud cases)

---

## 🛠️ Tech Stack & Tools
- **Programming Language:** Python
- **Libraries:**
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  - Imbalanced-learn (SMOTE)
- **Model:** Random Forest Classifier
- **Environment:** Jupyter Notebook

---

## 🔍 Methodology

### 1️⃣ Data Cleaning
- Checked for missing values (no major missing data found)
- Analyzed outliers in transaction amounts
- Assessed multicollinearity using correlation analysis
- Redundant features handled using feature selection techniques

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Identified strong class imbalance
- Analyzed transaction types and amounts
- Observed abnormal balance patterns in fraudulent transactions

---

### 3️⃣ Feature Selection
- Used **Recursive Feature Elimination with Cross-Validation (RFECV)**
- Selection based on **ROC-AUC score**
- Reduced multicollinearity and improved model stability

---

### 4️⃣ Model Building
- **Random Forest Classifier** chosen for:
  - Handling non-linear relationships
  - Robustness to outliers
  - Strong performance on imbalanced datasets
- **SMOTE** applied to balance
