# Diabetes Prediction using XGBoost

This is a self-initiated machine learning project focused on predicting the likelihood of diabetes using patient health data. The project leverages the power of the **XGBoost Classifier** to deliver strong predictive performance on a real-world dataset.

---

## 🧾 Objective

- Load and clean the dataset
- Handle categorical and numerical variables
- Apply feature scaling
- Train a predictive model using XGBoost
- Evaluate using standard classification metrics

---

## 📊 Dataset

The dataset includes the following features:

- `age`, `gender`, `hypertension`, `heart_disease`
- `smoking_history`, `bmi`, `HbA1c_level`, `blood_glucose_level`
- Target variable: `diabetes` (binary: 0 or 1)

---

## 🧹 Preprocessing

- Handled missing values in the gender column
- Encoded categorical features using `get_dummies`
- Scaled numerical features using `StandardScaler`

---

## 🧠 Model

- **Algorithm**: XGBoost Classifier
- **Train/Test Split**: 80/20
- **Input**: Scaled numerical and one-hot encoded features

---

## ✅ Performance

| Metric     | Value   |
|------------|---------|
| Accuracy   | ~96.6%  |
| Precision  | ~97.8%  |
| Recall     | ~70.0%  |
| ROC-AUC    | ~0.98   |

The model shows strong accuracy, precision, recall and ROC-AUC  

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `xgboost`
- `sklearn`
- `matplotlib` / `seaborn` 

---

## 📌 Notes

This project was created as part of my personal learning journey in Machine Learning to deepen my skills with real-world datasets and XGBoost.

---

## 🚀 Tags

`#MachineLearning` `#XGBoost` `#DiabetesPrediction` `#MLProjects`
