# Telco Customer Churn Prediction

## 📌 Project Overview
This project analyzes customer churn for a telecom company and builds a predictive model to identify customers most likely to leave.  
The analysis stops at Block 4 — providing a cleaned dataset, churn rate calculation, a baseline Logistic Regression model, and complete model evaluation.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📂 Work Completed (Until Block 4)

### **Block 1 — Data Cleaning & Encoding**
- Cleaned and standardized column names.
- Handled missing values.
- Converted `TotalCharges` to numeric and removed rows with missing values.
- Dropped ID columns.
- Encoded `Churn` as binary (1 = churn, 0 = no churn).
- One-hot encoded categorical variables.
- Calculated churn rate as a baseline KPI.

### **Block 2 — Train/Test Split**
- Split data into training (80%) and testing (20%) sets.
- Preserved churn rate distribution using stratified sampling.

### **Block 3 — Logistic Regression Model**
- Standardized features using `StandardScaler`.
- Trained a Logistic Regression model with class balancing.
- Generated predictions on the test set.
- Calculated accuracy, precision, recall, F1-score, and AUC.

### **Block 4 — Model Evaluation**
- Created a confusion matrix to visualize model performance.
- Produced a classification report for churn vs. non-churn customers.

---

## 📊 Key Insight
- Churn Rate: ~26% (meaning ~26 out of every 100 customers leave).
- Model provides a baseline to identify at-risk customers for targeted retention campaigns.

---

## 🚀 Next Steps (Optional Enhancements)
- Threshold tuning to optimize recall for retention strategies.
- Feature importance analysis to identify churn drivers.
- Dashboard or app integration for business use.

---

## 📜 Dataset
- **Source:** Telco Customer Churn dataset (`Telco churn rates.csv`)
- Contains demographic, service, and billing information for telecom customers.
