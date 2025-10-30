# 💓 Heart Disease Classification using Machine Learning

This project focuses on building and evaluating multiple machine learning models to **predict the presence of heart disease** based on patient health data.  
The dataset used is the classic **UCI Heart Disease dataset**, containing 303 patient records and 14 attributes.

---

## 🚀 Project Overview

The goal of this project is to:
- Analyze the dataset and handle missing values (if any)
- Perform **data preprocessing and encoding**
- Train and compare **three ML models**:
  - Logistic Regression  
  - Random Forest Classifier  
  - XGBoost Classifier  
- Evaluate performance using **Accuracy, Precision, Recall, F1-Score**, and **MSE**
- Save the best-performing model for future predictions

---

## 🧩 Dataset

**File:** `heart.csv`  
**Shape:** `303 rows × 14 columns`  
**Target Column:** `target`  
- `1` → Heart Disease Present  
- `0` → No Heart Disease  

### Main Features
| Feature | Description |
|----------|-------------|
| age | Age in years |
| sex | Gender (1 = male, 0 = female) |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl |
| restecg | Resting electrocardiographic results |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy |
| thal | Thalassemia type |
| target | 1 = Heart disease, 0 = No heart disease |

---

## ⚙️ Model Training Pipeline

### Steps:
1. **Load & Explore Data**
2. **Check Missing Values**
3. **Encode Categorical Columns**
4. **Split Dataset into Train & Test**
5. **Train Models:**
   - Logistic Regression
   - Random Forest
   - XGBoost
6. **Evaluate Models using Metrics**
7. **Save Best Model**

---

## 📊 Model Performance Summary

| Model | Accuracy | Precision | Recall | F1 Score | MSE |
|--------|-----------|------------|---------|----------|------|
| Logistic Regression | 0.80 | 0.77 | 0.91 | 0.83 | 0.19 |
| Random Forest | **0.82** | 0.76 | **0.97** | **0.85** | **0.18** |
| XGBoost | 0.80 | 0.76 | 0.94 | 0.84 | 0.19 |

✅ **Best Model:** Random Forest Classifier  
✅ **Saved Model:** `best_heart_model.joblib`

---

## 🧠 How to Use

Heart-Disease-Prediction/
│
├── Heart Disease.ipynb         # Jupyter Notebook containing data preprocessing, EDA, training & evaluation
├── best_heart_model.joblib     # Final trained ML model (Pipeline-based)
├── heart.csv                   # Dataset used for model training
├── README.md                   # Project documentation file (this file)



