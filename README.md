# 🩺 Diabetes Prediction using Machine Learning

This project focuses on predicting whether a patient is **likely to have diabetes** based on diagnostic measurements.  
It leverages supervised machine learning algorithms to perform **binary classification** on healthcare data.

---

## 📘 Project Overview

Diabetes is one of the most common chronic diseases globally.  
Early detection and prevention are critical to managing and reducing its impact.  
This project aims to build a model that predicts diabetes using patient health data such as glucose levels, BMI, blood pressure, and more.

---

## 🧠 Objective

To create a **predictive machine learning model** that classifies patients as:
- **1 (Positive):** Diabetic  
- **0 (Negative):** Non-Diabetic

---

## 🧩 Dataset Details

- **Dataset Name:** PIMA Indians Diabetes Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes)
- **Number of Instances:** 768  
- **Number of Attributes:** 8 numeric features and 1 target label  

### 🔢 Features:
| Feature | Description |
|----------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body Mass Index (weight in kg/(height in m)^2) |
| DiabetesPedigreeFunction | Diabetes heredity score |
| Age | Age in years |
| Outcome | Target variable (1 = Diabetic, 0 = Non-Diabetic) |

---

## ⚙️ Technologies Used

- Python 🐍  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 🧮 Steps Performed

1. **Data Loading and Exploration**
   - Checked shape, missing values, and feature statistics.
   - Visualized feature correlations and class balance.

2. **Data Preprocessing**
   - Handled invalid zeros in columns like `Glucose`, `BMI`, `BloodPressure`.
   - Normalized/standardized features for better model convergence.

3. **Model Building**
   - Trained a **Logistic Regression** classifier.
   - Split data into training and testing sets (e.g., 80:20).

4. **Model Evaluation**
   - Evaluated using:
     - Accuracy
     - Confusion Matrix
     - Precision, Recall, and F1-Score
   - Compared performance between training and testing data.

5. **Prediction System**
   - Created a custom input-based prediction system to predict diabetes status.

---

## 📊 Results

| Metric | Train Accuracy | Test Accuracy |
|:-------:|:---------------:|:--------------:|
| Logistic Regression | ~80% | ~78% |

*(Results may vary depending on preprocessing and random split)*

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Varugowdatp/diabetes_prediction.git
2. Run in the resoective repo
