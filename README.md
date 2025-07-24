# 🏦 Loan Prediction using Random Forest

This project aims to predict whether a loan application will be approved or not using a **Random Forest Classifier**. It involves building an end-to-end machine learning pipeline including data preprocessing, hyperparameter tuning, model evaluation, and cross-validation.

## 📌 Problem Statement
Financial institutions need to make reliable decisions on loan approvals to minimize risk. By leveraging machine learning, we can help automate and improve the accuracy of these decisions based on customer data.

---

## 📊 Dataset
The dataset includes features like:
- Applicant Income
- Coapplicant Income
- Loan Amount
- Credit History
- Gender, Marital Status, Education, Property Area, etc.

Target variable: `Loan_Status` (Accepted/Rejected)

---

## 🧪 Project Workflow

1. **Data Loading and Exploration**
2. **Data Cleaning**
   - Handling missing values
   - Encoding categorical features
   - Feature scaling
3. **Train-Test Split with Stratified K-Fold**
4. **Model Building**
   - Pipeline with `StandardScaler`, `OneHotEncoder`, and `RandomForestClassifier`
5. **Hyperparameter Tuning**
   - Using `RandomizedSearchCV`
6. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
   - ROC Curve and AUC Score

---

## 🔧 Tools & Technologies
- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

---

## ✅ Results
- **Train Accuracy:** 99%
- **Test Accuracy:** 97%
- **AUC Score:** ~0.998
- Well-balanced precision and recall
- Clean ROC curve and minimal overfitting
