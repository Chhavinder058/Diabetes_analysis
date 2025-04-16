
# 📊 Diabetes Analysis: Predicting Readmissions

A complete end-to-end analysis and prediction of hospital readmission in diabetic patients using machine learning.

---

## 🚀 Project Overview

This project leverages a real-world dataset of over 100,000 diabetic patient records to:

- Explore trends and patterns that contribute to hospital readmission
- Apply logistic regression and random forest models to predict outcomes
- Visualize key insights to inform healthcare decision-making

---

## 📊 Key Findings

- Most readmitted patients are above 60 years old
- Patients with more diagnoses, inpatient stays, and medications have a higher risk
- Random Forest performed better than Logistic Regression, but recall can still improve

---

## 🤖 Models Used

| Model              | Accuracy | ROC AUC |
|-------------------|----------|---------|
| Logistic Regression | 62%      | 0.57    |
| Random Forest       | 58%      | 0.58    |

✅ Evaluation includes confusion matrix, classification report, and feature importances.

---

## 📈 Visual Output Samples

![](charts/age_dist.png)  
*Figure: Age Distribution of Patients*

![](charts/conf_matrix.png)  
*Figure: Random Forest Confusion Matrix*

---

## 🧰 How to Run This Project

```bash
# Step 1: Clone the repo
git clone https://github.com/Chhavinder058/Diabetes_analysis.git

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run notebook
jupyter notebook notebooks/Healthcare_EDA.ipynb
