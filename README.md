# 🚢 Titanic Dataset – Data Cleaning & Preprocessing

## 📌 Task Overview

This task focuses on cleaning and preparing the Titanic dataset for machine learning. I followed a step-by-step process to handle missing values, encode categorical variables, scale features, and remove outliers.

---

## 🛠️ Steps I Followed

### 1. Loaded the Dataset
- Imported the Titanic dataset using pandas.
- Checked basic info, data types, and missing values.

### 2. Handled Missing Values
- Filled missing `Age` values using the **median**.
- Replaced missing values in `Cabin` with **'Unknown'**.
- Filled missing values in `Embarked` with the **mode** (most frequent value).

### 3. Encoded Categorical Variables
- Converted `Sex` to numeric: `male = 0`, `female = 1`.
- Used **one-hot encoding** for `Embarked`.
- Dropped columns like `Name` and `Ticket` (not useful for modeling).

### 4. Standardized Numerical Features
- Standardized `Age`, `Fare`, `SibSp`, and `Parch` using **StandardScaler** so all values are on the same scale.

### 5. Detected and Removed Outliers
- Plotted **boxplots** to visualize outliers.
- Removed outliers using the **IQR (Interquartile Range)** method.

---

## ✅ Final Output

- Cleaned and preprocessed dataset.
- All features are numeric and ready for machine learning models.
- Outliers and null values have been handled properly.

---

## 📂 Files Included
- `Task1_Data_Cleaning_Preprocessing.ipynb` – Jupyter notebook with step-by-step code.
- `Titanic-Dataset.csv` – The dataset used for this task.

---

## 🔗 Dataset Source
[Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

