# 🏦 Credit Risk Scoring Model

This project demonstrates a machine learning pipeline for **credit risk scoring** using a real-world dataset. The goal is to predict whether a loan is high-risk (`1`) or low-risk (`0`) based on applicant information.

---

## 📊 Dataset

The dataset contains information about borrowers and their loan status. Features include numerical and categorical variables relevant to credit history and applicant details.

- **Target Variable:** `loan_status`  
- **Classes:**  
  - `0` = Low Risk  
  - `1` = High Risk  

---

## ⚙️ Model Used

- **Algorithm:** Random Forest Classifier  
- **Train-Test Split:** 80-20  
- **Preprocessing:**  
  - Dropped missing values  
  - Label encoded categorical features  

---

## 📈 Evaluation Metrics

| Metric          | Score    |
|-----------------|----------|
| Accuracy        | 93%      |
| Precision (1)   | 98%      |
| Recall (1)      | 71%      |
| F1-score (1)    | 82%      |
| ROC AUC Score   | 0.93     |

> 🔍 High recall for class `0` (low risk) and precision for class `1` (high risk) indicate a strong ability to distinguish risk types.

---

## 📊 Visualizations

- Loan Status Distribution
- Feature Correlation Heatmap
- Feature Importance Bar Chart
- ROC Curve

---
