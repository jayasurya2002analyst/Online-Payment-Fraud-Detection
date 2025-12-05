# Online-Payment-Fraud-Detection
“Data Preprocessing &amp; Feature Engineering for Online Payment Fraud Detection using Python
# 🏦 Online Payment Fraud Detection — Data Preprocessing Project

This project focuses on cleaning, preprocessing, and feature engineering of an Online Payment Fraud dataset to prepare it for machine learning models.

---

## 🎯 Objectives
- Understand fraud patterns in online transactions  
- Perform intermediate-level data cleaning  
- Handle missing values and outliers  
- Encode categorical features  
- Scale numerical features  
- Create new fraud-relevant features  
- Export a clean dataset for ML modelling  

---

## 🛠 Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-Learn**

---

## 📂 Files Included
| File | Description |
|------|-------------|
| `day14_payment_preprocessing.ipynb` | Full preprocessing notebook |
| `payment_fraud_clean.csv` | Final cleaned dataset |
| `README.md` | Project documentation |

---

## 📌 Preprocessing Tasks Completed
- Dataset inspection (`head`, `info`, `describe`)
- Missing value detection & treatment
- Duplicate removal
- Outlier detection using IQR method
- Encoding `type` column (One-Hot Encoding)
- Scaling numerical columns (StandardScaler)
- Feature engineering:
  - `balance_difference`
  - `high_amount_flag`
- Exported cleaned dataset

---

## 📊 Key Insights
- Fraud dataset is **highly imbalanced**
- Large transactions tend to have higher fraud probability
- Balance mismatch can indicate suspicious activities

---

## 🚀 Next Steps (Day-15)
- Perform full EDA  
- Build Fraud Classification ML Models  
- Evaluate using ROC-AUC, Precision, Recall  

---

⭐ *Follow for more projects. Feel free to fork or reuse for learning!*  
