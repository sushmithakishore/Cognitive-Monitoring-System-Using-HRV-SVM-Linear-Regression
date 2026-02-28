# 📉 Cognitive Monitoring System Using HRV, SVM & Linear Regression

## 📌 Overview

This project develops a machine learning–based cognitive monitoring framework using Heart Rate Variability (HRV) features to assess cognitive state and neurological risk patterns. The objective is to analyze physiological signal variations and model their relationship with cognitive decline indicators using supervised learning techniques.

The system implements a complete machine learning pipeline including signal preprocessing, HRV feature extraction, model training, and predictive performance evaluation.

---

## 🧪 Methodology

### 1️⃣ Signal Preprocessing
- Noise reduction and artifact removal from HRV signals  
- Handling missing physiological readings  
- Time-domain signal normalization  
- Structured formatting of HRV datasets  

### 2️⃣ Feature Engineering
- Extraction of time-domain HRV metrics (Mean RR, SDNN, RMSSD)  
- Frequency-domain HRV analysis  
- Correlation analysis between HRV features and cognitive indicators  
- Feature scaling and selection for model optimization  

### 3️⃣ Model Development
- Implementation of Support Vector Machine (SVM) for classification  
- Linear Regression modeling for cognitive score prediction  
- Hyperparameter tuning for optimal decision boundaries  
- Train-test splitting for generalization assessment  

### 4️⃣ Model Evaluation
- Accuracy, Precision, Recall, F1-Score  
- Confusion Matrix analysis  
- R² Score for regression performance  
- Comparative evaluation of SVM and Linear Regression models  

---

## 🛠️ Tech Stack

- **Programming:** Python  
- **Data Processing:** Pandas, NumPy  
- **Modeling:** Scikit-learn (SVM, Linear Regression)  
- **Signal Analysis:** HRV Feature Extraction  
- **Visualization:** Matplotlib, Seaborn  
- **Evaluation Metrics:** Scikit-learn  

---

## 🎯 Objective

To design a predictive cognitive monitoring framework that leverages HRV-based physiological biomarkers to model cognitive state patterns using machine learning techniques.
