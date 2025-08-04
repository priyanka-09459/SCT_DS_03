# 🌳 Task 3 – Bank Marketing Classification

This repository contains the implementation of a **Decision Tree Classifier** using the **Bank Marketing Dataset**, completed as part of **Task 3** in the SkillCraft Data Science internship.

---

## 📁 Files Included

```
task3/
├── skillcraft_task3.ipynb

```

---

## 📌 Objective

- Clean the bank marketing dataset
- Encode categorical columns using LabelEncoder
- Train a Decision Tree Classifier to predict client subscription (`y`)
- Evaluate the model’s performance

---

## 🔍 Process Overview

- Dataset parsing (semicolon-separated Excel content)
- String cleanup and header renaming
- Label encoding of object columns
- Model training using `DecisionTreeClassifier`
- Performance measured using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix Visualization

---

## ✅ Results

- **Accuracy:** `~82.88%`
- **Precision & Recall** weighted toward majority class
- Visual confusion matrix showed a clear prediction boundary

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Jupyter Notebook

---

## 🚀 Run Instructions

1. Clone this repo:
   ```bash
   git clone https://github.com/priyanka-09459/SCT_DS_03.git
   cd SCT_DS_03
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook:
   ```bash
   jupyter notebook skillcraft_task3.ipynb
   ```

---

## 📬 Author

👩‍💻 **Priyanka Swain**
📂 [GitHub](https://github.com/priyanka-09459/SCT_DS_03)

---
