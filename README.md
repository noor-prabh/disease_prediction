# 🧠 Disease Prediction from Medical Data (Two Datasets)

This project uses machine learning to predict diseases from structured medical data. It works with two healthcare datasets: **Breast Cancer** and **Diabetes**, both available from scikit-learn.

---

## 📌 Objective

To predict whether a patient is likely to have a disease based on medical features like glucose level, age, cell nucleus properties, and more.

---

## 📊 Datasets Used

1. **Breast Cancer Dataset**
   - Source: `sklearn.datasets.load_breast_cancer()`
   - Task: Predict if a tumor is malignant or benign

2. **Diabetes Dataset**
   - Source: `sklearn.datasets.load_diabetes()` (used as a classification task by thresholding target)
   - Task: Predict if a person is diabetic (converted to classification)

---

## 🤖 Algorithms Used

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 🔍 Highlights

- Runs predictions for two different datasets in one script  
- Compares model performance across multiple algorithms  
- Clean, simple structure for easy understanding  
