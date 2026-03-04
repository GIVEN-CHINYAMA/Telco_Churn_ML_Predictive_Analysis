# 📞 Telco Customer Churn: Predictive Machine Learning Analysis

![Python](https://img.shields.io) ![Scikit-Learn](https://img.shields.io) ![Machine Learning](https://img.shields.io)

## 📌 Business Problem
Customer churn is a critical KPI for telecommunications companies. It costs **5x more** to acquire a new customer than to retain an existing one. This project develops a predictive model to identify high-risk customers, allowing for proactive retention marketing.

## 🛠️ Data Science Workflow
1. **EDA & Visualization:** Analyzed 7,000+ records to identify behavioral patterns.
2. **Preprocessing:** 
   - Handled imbalanced classes using **SMOTE** (Synthetic Minority Over-sampling Technique).
   - Encoded categorical variables (One-Hot Encoding).
   - Scaled numerical features using **StandardScaler**.
3. **Modeling:** Evaluated Logistic Regression, Random Forest, and XGBoost.
4. **Optimization:** Hyperparameter tuning using **GridSearchCV**.

## 💡 Strategic Business Insights
*   **Contract Risk:** Month-to-month contracts have a **churn rate of 42%**, compared to <7% for two-year contracts.
*   **Fiber Optic Vulnerability:** Customers with Fiber Optic service churn at a higher rate, likely due to pricing or service reliability issues.
*   **Tenure Threshold:** Customers who stay past **24 months** show 80% higher lifetime loyalty.

## 📊 Model Results
*   **Accuracy:** 81%
*   **Recall (Churn):** 76% (Prioritized recall to ensure we don't miss at-risk customers)
*   **AUC-ROC:** 0.85

## 🚀 Quick Start
```bash
git clone https://github.com
pip install -r requirements.txt
jupyter notebook Telco_Churn_Analysis.ipynb


📬 Contact & Connect
LinkedIn: given-chinyama-data
GitHub: GIVEN-CHINYAMA
Email: givenchinyama@gmail.com
