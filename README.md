# 👩‍💼 Employee Attrition Prediction
Employee Attrition Prediction is the process of using historical employee data and machine learning techniques to forecast which employees are likely to leave an organization in the near future. By analyzing factors such as age, salary, tenure, department, overtime, job role, and work-life balance, these predictive models help identify patterns that indicate a higher risk of attrition. The goal is to enable HR and management to take proactive measures to retain valuable employees, reduce turnover-related costs, and improve overall workforce stability. Models are typically evaluated using metrics like recall, precision, and accuracy, with recall often prioritized to minimize false negatives, ensuring employees at risk of leaving are correctly identified.



 ✅ Techniques & Models

**Supervised Learning Models:**

* Gaussian Naive Bayes *(Best Recall: 0.67)*
* Logistic Regression, Decision Tree, Random Forest, SVM
* Gradient Boosting, XGBoost, K-Nearest Neighbors

**Preprocessing & Feature Engineering:**

* Categorical encoding: Label & One-Hot
* Z-score normalization
* Handling class imbalance with **SMOTE**

---
 📊 Exploratory Data Analysis (EDA)

* Attrition trends by **Age, Gender, Salary, Department**
* Correlation heatmaps for numerical features
* Outlier detection & treatment
* Insights on **Overtime** and **Distance-from-Home** patterns

---

## 🚀 Tools & Environment

* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`, `plotly`
* **Imbalance Handling:** `imbalanced-learn` (SMOTE)

---

 📈 Model Performance

| Model             | Accuracy | Recall   | Precision | F1 Score |
| ----------------- | -------- | -------- | --------- | -------- |
| Naive Bayes       | 84.7%    | **0.67** | 0.36      | 0.47     |
| Gradient Boosting | 89.0%    | 0.41     | 0.64      | 0.50     |
| Random Forest     | 88.8%    | 0.41     | 0.61      | 0.49     |
| SVM               | 90.1%    | 0.38     | 0.76      | 0.50     |

> Note: Recall was prioritized to help HR identify at-risk employees effectively.

---

 



