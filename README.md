# 📊 Customer Churn Prediction

## 🔍 Overview
This project predicts customer churn using machine learning to help businesses identify customers likely to leave.

---

## 📊 Key Insights
- Higher monthly charges → higher churn  
- Contract type significantly affects churn  

---

## 🤖 Models & Results

### Logistic Regression
- Accuracy: 77.9%  
- ROC-AUC: 0.62  
- Recall (Churn): 30%  

### Random Forest
- Accuracy: 78.7%  
- ROC-AUC: 0.67  
- Recall (Churn): 44%  

👉 Random Forest performed better, especially in detecting churn customers.

---

## ⚠️ Challenges
- Class imbalance  
- Low recall for churn prediction  

---

## 🚀 Improvements
- SMOTE (oversampling)  
- Hyperparameter tuning  
- Advanced models (XGBoost)  

---

## 🛠️ Tech Stack
Python | Pandas | NumPy | Matplotlib | Scikit-learn  

---

## 📌 Conclusion
Random Forest improved performance, but detecting churn customers remains challenging. This project highlights the importance of recall and ROC-AUC over accuracy.

---

## 👤 Author
Amish Kumar
