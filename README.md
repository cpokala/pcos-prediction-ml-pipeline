# 🧠 PCOS Prediction Pipeline: From Data Cleaning to Machine Learning

This project presents a comprehensive machine learning pipeline for diagnosing **Polycystic Ovary Syndrome (PCOS)** using clinical and lifestyle data. Starting from raw data cleaning to model evaluation, it walks through essential steps in building a predictive system that can help in early detection and decision support.

---

## 📂 Project Structure

- `Intro_to_Info_PCOS_Project.ipynb`: Main Jupyter notebook containing all steps from data preprocessing to model evaluation.
- `PCOS_data_without_infertility.xlsx`: Dataset containing medical and lifestyle attributes for women with/without PCOS.

---

## 🔍 Key Features

### ✅ Data Preprocessing
- Missing value imputation (median/mode)
- Type casting & encoding
- Column renaming and feature cleanup
- Handling of non-numeric values

### 📊 Exploratory Data Analysis
- Summary statistics
- Distribution of key features
- Outlier detection

### 🤖 Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

### 📈 Model Evaluation
- F1-score (Train/Test)
- Confusion Matrix
- ROC Curve visualization

---

## 📊 Dataset Overview

- **Source:** 'Kaggle'
- **Target Variable:** `PCOS (Y/N)`
- **Features:** Hormone levels, BMI, menstrual history, fast food habits, marital status, etc.

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/pcos-prediction-pipeline.git
   cd pcos-prediction-pipeline
