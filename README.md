# 📊 Customer Churn Prediction

## 🧠 Problem

Customer churn is a major problem in telecom companies.
The goal is to predict whether a customer will churn or not.

---

## 🔍 EDA (Exploratory Data Analysis)

Key insights:

* Data is imbalanced (more "No" than "Yes")
* Customers with month-to-month contracts churn more
* Low tenure customers have higher churn
* Higher monthly charges → higher churn risk

---

## 🧹 Data Cleaning

* Removed irrelevant features (customerID)
* Handled missing values
* Applied encoding (one-hot encoding)

---

## ⚙️ Feature Engineering

* Created new features:

  * AvgCharge
  * IsNewCustomer
* Applied scaling where needed

---

## 🤖 Models Used

* Logistic Regression
* Decision Tree
* Random Forest

---

## 📊 Evaluation Metrics

* Precision
* Recall
* F1-score (main metric)

---

## ⚖️ Handling Imbalance

* Used:

  * class_weight = balanced
  * SMOTE

---

## 🔥 Final Model

Random Forest:

* max_depth = 10
* class_weight = balanced
* threshold = 0.5

---

## 📈 Final Results

* Precision: ~0.53
* Recall: ~0.70
* F1-score: ~0.60

---

## 💼 Business Impact

* Identify high-risk customers early
* Reduce churn through targeted actions
* Optimize marketing cost

---

## 🚀 Conclusion

Random Forest with threshold tuning provided the best balance between precision and recall, making it suitable for real-world deployment.
