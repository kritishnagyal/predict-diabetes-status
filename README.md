# 🩺 Diabetes Prediction Using Machine Learning

This repository contains a machine learning project that predicts whether a person is **diabetic or not** using health-related input features. It utilizes a **binary classification model** trained on the well-known **Pima Indians Diabetes Dataset**.

---

## 💡 Problem Statement

The goal of this project is to create a supervised machine learning model that classifies individuals into **Diabetic** or **Non-Diabetic** based on medical attributes like:
- Glucose level
- Blood pressure
- Insulin levels
- BMI, and more...

This prediction can be valuable in **early diagnosis and medical planning**.

---

## 📊 Dataset Overview

The dataset used is `diabetes.csv`, a version of the **Pima Indians Diabetes Database** originally from the UCI Machine Learning Repository.

### 🔹 Dataset Features:
- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skin fold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function
- `Age`: Age (years)
- `Outcome`: 0 = Non-Diabetic, 1 = Diabetic (Target)

---

## 🛠️ Project Workflow

1. **Data Preprocessing**  
   - Handle missing or zero values in some medical measurements
   - Normalize data if necessary
   - Split into training and testing sets

2. **Exploratory Data Analysis (EDA)**  
   - Correlation heatmap
   - Distribution plots
   - Class balance analysis

3. **Model Building**  
   - Supervised classification algorithms like:
     - Logistic Regression
     - Random Forest
     - K-Nearest Neighbors
     - Decision Tree

4. **Model Evaluation**  
   - Accuracy Score
   - Confusion Matrix
   - Precision, Recall, F1-score

5. **Prediction & Visualization**  
   - Predict test results
   - Visualize performance and compare models

---

## 📁 Repository Contents

```bash
├── Diabetic_or_not.ipynb         # Jupyter notebook with code and visualizations
├── README.md                     # Project documentation
└── diabetes.csv                  # Dataset used for training and testing
