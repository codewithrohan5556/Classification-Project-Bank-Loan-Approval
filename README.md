# 🏦 Loan Approval Prediction - Classification Project


## 🔍 Introduction
This project aims to predict loan eligibility using machine learning classification algorithms. It automates the loan approval process based on applicant data like income, credit history, and loan amount—streamlining decision-making in financial institutions.

---

## 🧩 Problem Statement
Dream Housing Finance needs a model to identify which customers are likely to be approved for home loans based on their application details. This will reduce manual effort, ensure consistency, and improve turnaround time.

---

## 🎯 Objective
- Analyze factors affecting loan approval.
- Build and evaluate multiple classification models.
- Automate prediction of loan eligibility.
- Offer recommendations for future improvements.

---

## 📁 Dataset
The dataset contains information such as:
- Gender, Marital Status, Dependents
- Education, Self-Employed
- Applicant & Coapplicant Income
- Loan Amount & Term
- Credit History, Property Area
- Loan Status (Target Variable)

---

## 📊 Exploratory Data Analysis (EDA)
- Visualized feature distributions
- Handled missing values
- Detected outliers and categorical inconsistencies

---

## 🧠 Model Building
Tested the following models:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

**Best Model:** Random Forest (balanced accuracy & interpretability)

---

## ✅ Conclusion & Insights
- Credit history is the most influential feature.
- Income and loan amount greatly affect approval chances.
- Proper preprocessing (e.g., encoding, imputation) boosts performance.

---

## 🚀 Future Scope
- Deploy as a web app using Streamlit/Flask
- Add SHAP/LIME for model explainability
- Incorporate real-time scoring with new features like credit score
- Improve fairness through bias analysis
- Implement model monitoring for live predictions

---

## 🛠 Tools Used
- Python, Pandas, NumPy
- Scikit-learn, Matplotlib, Seaborn
- Jupyter Notebook
- GitHub

---

<h2>📁 Project Structure</h2>
  <pre><code>
zomato-data-analysis/
├── data/
├── images/
├── notebooks/
├── src/
├── README.md
├── requirements.txt
└── LICENSE
  </code></pre>
  
## ✅ Conclusion & Analysis
The loan approval prediction model accurately identifies eligible applicants by analyzing patterns in income, employment, credit history, and loan terms. Among all models tested, Logistic Regression and Random Forest Classifier provided the best balance between accuracy and interpretability.

Key findings:
- Credit history has the highest impact on loan approval.

- Applicants with higher income and fewer dependents have better approval chances.

- Loan amount and term show moderate impact, especially when combined with income data.

- Preprocessing steps like imputing missing values and label encoding significantly improved performance.

- This solution not only reduces manual effort but also ensures fairer, data-driven decisions—especially beneficial for large-scale financial operations.

