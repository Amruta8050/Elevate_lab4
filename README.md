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

#Outputs
<img width="1439" height="441" alt="Image" src="https://github.com/user-attachments/assets/40bababb-6a1f-4f78-8b0e-746fb3aabbbb" />
<img width="469" height="560" alt="Image" src="https://github.com/user-attachments/assets/760309d8-0e5f-4d27-8c0b-efc6f739ec73" />
<img width="308" height="720" alt="Image" src="https://github.com/user-attachments/assets/be613bb2-4fc8-4842-84da-34295789aa67" />
<img width="334" height="363" alt="Image" src="https://github.com/user-attachments/assets/2b8e5562-2124-4971-b8a0-d563cef1432b" />
<img width="1481" height="346" alt="Image" src="https://github.com/user-attachments/assets/636bced3-67e6-4031-b162-9316904b811d" />
<img width="1162" height="493" alt="Image" src="https://github.com/user-attachments/assets/0453fc5f-0bd5-495e-9a51-c41c86b2e5b0" />
<img width="1240" height="493" alt="Image" src="https://github.com/user-attachments/assets/7eb11898-fb04-4a42-b7cc-3d956c2de736" />
