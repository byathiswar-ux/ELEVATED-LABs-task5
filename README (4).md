
# Task 5

# Project Overview
This project is part of the **AI & ML Internship – Task 5**, focused on understanding **model evaluation fundamentals** using the **Heart Disease Dataset**.

The task demonstrates how to:
- Split data into training and testing sets
- Train a Logistic Regression model
- Evaluate performance using accuracy, precision, recall, and confusion matrix
- Interpret results with a healthcare perspective

---

# Tools & Technologies
- Python
- Google Colab
- Scikit-learn
- Pandas
- NumPy

---

# Dataset
**Heart Disease Dataset**
- Target column: `target`
  - `0` → No heart disease
  - `1` → Heart disease present

---

# Steps Performed

# 1. Data Loading
- Loaded the dataset using Pandas
- Checked structure and missing values

# 2. Train-Test Split
- Split data into **80% training** and **20% testing**
- Ensures unbiased model evaluation

# 3. Feature Scaling
- Applied `StandardScaler` to normalize features
- Improves Logistic Regression performance

# 4. Model Training
- Used **Logistic Regression**
- Applied `class_weight='balanced'` to handle class imbalance

# 5. Evaluation Metrics
- **Accuracy**
- **Precision**
- **Recall**
- **Confusion Matrix**

---

# Why Recall Is Important
In medical diagnosis:
- **False Negatives** (missing a disease case) are dangerous
- Therefore, **Recall is prioritized** over Precision

---

# Results Interpretation
- High recall indicates the model successfully identifies most heart disease patients
- Precision is kept at an acceptable level to avoid excessive false alarms
- Balanced performance makes the model suitable for healthcare screening

# Output
 <img width="1238" height="455" alt="Image" src="https://github.com/user-attachments/assets/0b6e395e-23e3-4055-9d7c-29deb1ebc1c3" />
<img width="1131" height="609" alt="Image" src="https://github.com/user-attachments/assets/ea1278e2-2adf-4c27-a58a-3c8fd0d49f1d" />
<img width="992" height="591" alt="Image" src="https://github.com/user-attachments/assets/d4bf2a4a-3c4f-49bb-b5de-ccd0966be307" />
<img width="739" height="435" alt="Image" src="https://github.com/user-attachments/assets/acc7a3ac-eedf-4e7d-8fe4-ba11d8d8a3a3" />
<img width="1124" height="562" alt="Image" src="https://github.com/user-attachments/assets/b6711c73-2407-4782-8647-818d97c00f72" />
