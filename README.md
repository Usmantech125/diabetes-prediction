# 🧠 Diabetes Prediction using SVM

This project is part of my internship with **Codveda**. The goal is to predict whether a patient is likely to have diabetes using Support Vector Machine (SVM) models based on medical and demographic data.

---

## 📁 Dataset

- File: `diabetes_prediction_dataset.csv`
- Target Variable: `diabetes` (0 = No, 1 = Yes)
- Features: age, gender, BMI, HbA1c level, blood glucose, hypertension, smoking history, etc.

---

## 🛠️ Tools & Technologies Used

- Python
- pandas, NumPy
- scikit-learn
- SVM (Support Vector Machine)
- StandardScaler
- Performance Metrics: Accuracy, Precision, Recall, AUC

---

## 🔧 Project Workflow

### 1. Data Preprocessing
- One-hot encoded `smoking_history`
- Label encoded `gender` (Male = 1, Female = 0)
- Removed missing values
- Scaled numerical features using `StandardScaler`

### 2. Model Building
- Implemented SVM with:
  - Linear Kernel
  - RBF Kernel

### 3. Evaluation
Used the following metrics to compare models:
- Accuracy
- Precision
- Recall
- AUC (Area Under ROC Curve)

---

## 📈 Results

| Kernel | Accuracy | Precision | Recall | AUC |
|--------|----------|-----------|--------|-----|
| Linear | ✅       | ✅        | ✅     | ✅  |
| RBF    | ✅       | ✅        | ✅     | ✅  |

> (Replace ✅ with actual metric values from your output)

---

## 📌 Conclusion

This project demonstrates the application of SVM for binary classification problems in healthcare. Both linear and non-linear kernels were explored and evaluated for performance.

---

## 🚀 Author

**Usman Ghani**  
Codveda Internship 2025  
GitHub: [Your GitHub Link]  
LinkedIn: [Your LinkedIn Profile]
