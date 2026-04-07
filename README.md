# 🏦 Loan Approval Prediction using Fairness-Aware Machine Learning

## 📌 Project Overview
This project aims to predict whether a loan application should be approved or rejected using machine learning models. It also focuses on **fairness-aware prediction** to reduce bias in decision-making.

---

## 🎯 Problem Statement
Banks often rely on manual or biased systems for loan approval. This project solves that by:
- Automating loan approval decisions using ML
- Ensuring fair predictions across different groups (e.g., gender)

---

## 📊 Dataset
- Dataset used: Loan Prediction Dataset
- Features include:
  - Gender
  - Married
  - Education
  - Applicant Income
  - Loan Amount
  - Credit History
- Target variable:
  - `Loan_Status` (Approved / Not Approved)

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🤖 Machine Learning Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## 🔄 Project Workflow
1. Data Collection
2. Data Preprocessing
   - Handling missing values
   - Encoding categorical variables
3. Feature Selection
4. Model Training
5. Model Evaluation
6. Fairness Analysis
7. Bias Reduction

---

## 📈 Model Performance

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 78.86%   |
| Decision Tree      | 71.54%   |
| Random Forest      | 78.05%   |
| SVM                | 79.67% ✅ |

---

## ⚖️ Fairness Analysis
- Compared approval rates between different groups (e.g., Gender)
- Identified bias in predictions
- Applied bias mitigation by removing sensitive features

---

## 📊 Visualizations
- Accuracy comparison graph
- Fairness comparison graph

---

## 🎯 Results
- SVM achieved the highest accuracy (~79.67%)
- Logistic Regression provided good interpretability
- Decision Tree showed lower performance due to overfitting
- Fairness improved after removing sensitive attributes

---

## ✅ Conclusion
This project successfully:
- Built an accurate loan prediction model
- Identified and reduced bias
- Demonstrated the importance of fairness in ML systems

---

## 🚀 Future Improvements
- Use advanced fairness algorithms
- Hyperparameter tuning
- Deploy as a web application



