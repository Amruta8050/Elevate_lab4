# Task 4: Feature Encoding & Scaling – Adult Income Dataset

## 📌 Overview
This project demonstrates **feature engineering techniques** required to prepare real-world data for Machine Learning models.  
The Adult Income Dataset is preprocessed using appropriate **encoding** and **scaling** strategies to make it model-ready.

This task is part of an **AI & ML Internship** focused on building strong data preprocessing fundamentals.

---

## 🎯 Objective
- Identify categorical and numerical features
- Apply correct encoding techniques
- Scale numerical data
- Compare data before and after scaling
- Save reusable, ML-ready datasets
- Understand the impact of scaling on ML algorithms

---

## 📂 Dataset
**Adult Income Dataset**  
Source: UCI Machine Learning Repository  

Target variable:
- `income` → predicts whether income is `>50K` or `<=50K`

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 🧠 Feature Engineering Strategy

### 1️⃣ Feature Identification
- **Categorical Features**: workclass, education, marital-status, occupation, etc.
- **Numerical Features**: age, fnlwgt, education-num, capital-gain, hours-per-week

---

### 2️⃣ Encoding Techniques
| Feature Type | Encoding Used | Reason |
|-------------|---------------|--------|
| Binary Target (`income`) | Label Encoding | Ordered output |
| Nominal Categorical | One-Hot Encoding | No inherent order |
| Numerical Features | StandardScaler | Required for ML models |

---

### 3️⃣ Scaling
- Applied **StandardScaler**
- Transforms features to:
  - Mean = 0
  - Standard Deviation = 1

---

## 📊 Why Scaling Matters
Scaling improves performance of:
- K-Nearest Neighbors (KNN)
- Support Vector Machines (SVM)
- Logistic Regression
- Gradient Descent–based models  

Not required for:
- Decision Trees
- Random Forests

---

## 📁 Project Structure
Task-4-Feature-Encoding-Scaling/
│
├── outputs/
│ ├── adult_encoded_before_scaling.csv
│ ├── adult_final_preprocessed.csv
│ ├── age_before_scaling.png
│ ├── age_after_scaling.png
│ └── report.txt
│
├── task4_feature_encoding.ipynb
└── README.md
