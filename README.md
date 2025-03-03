# 📌 Credit Risk Modelling v1.0
**A Machine Learning Approach for Credit Risk Analysis**

## 📖 Project Overview
This project focuses on **credit risk modeling** using machine learning techniques to predict the likelihood of mortgage loan default. The dataset consists of **fictitious mortgage loan records** as of **31st December 2022**. Various data preprocessing techniques, feature engineering, and classification models are applied to develop an accurate predictive model.

The primary goal is to identify key risk factors and build a model that helps financial institutions assess borrowers' creditworthiness.

---


## 🛠 Technologies Used
- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Machine Learning Models** (Logistic Regression, Decision Tree)
- **Visualization** (matplotlib, seaborn, Plotly)
- **Data Preprocessing** (Handling missing values, encoding categorical features)
- **Model Evaluation** (ROC-AUC, Precision-Recall, Confusion Matrix)

---

## 🔍 Data Overview
The dataset contains **fictitious mortgage loan records**, with features such as:
- **Loan Details:** Loan Amount, Loan Term, Loan-to-Value Ratio
- **Borrower’s Profile:** Credit Score, Account Management Score, Number of Late Payments
- **Historical Financial Data:** Days in Arrears, County Court Judgments, Public Information Sources

### Data Preprocessing
- **Handling missing values:** The dataset includes missing values represented as `.` which need to be converted and treated.
- **Feature Encoding:** Converting categorical data to numerical values.
- **Standardization:** Normalizing numerical features for better model performance.

---

## 🚀 Model Training & Evaluation
The following machine learning models were used:

### 1️⃣ Logistic Regression
- Used as the baseline model for credit risk classification.

### 2️⃣ Decision Tree Classifier
- Captures non-linear patterns in credit risk assessment.

### Performance Metrics
| Model                  | ROC-AUC | Precision | Recall |
|------------------------|---------|-----------|--------|
| Logistic Regression    | 0.75    | 0.68      | 0.72   |
| Decision Tree          | 0.82    | 0.74      | 0.76   |

✅ **Best Model:** **Decision Tree (82% ROC-AUC)**  
✅ **Key Insight:** Loan-to-Value ratio and Credit Score are among the most influential features.

---

## 📊 Results & Insights
📌 The Decision Tree model outperformed Logistic Regression in predicting loan defaults.  
📌 Key risk factors include **Loan-to-Value Ratio**, **Credit Score**, and **Days in Arrears**.  
📌 Feature importance analysis suggests that financial behavior significantly impacts default probability.

---

## 💡 Next Steps
🔹 Tune hyperparameters for better accuracy  
🔹 Test ensemble models (Random Forest, XGBoost)  
🔹 Try Model Calibration and Backtesting 

---
