# 🎓 Student Performance & At-Risk Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting **student academic performance** and identifying whether a student is **at risk** using Machine Learning techniques. The goal is to demonstrate an end-to-end ML workflow — from data cleaning and exploratory data analysis (EDA) to model training, evaluation, and interpretation.

The project solves two real-world problems:

1. **Regression** – Predicting a student's final score
2. **Classification** – Identifying whether a student is *at risk*

This kind of system can be used in educational institutions to proactively support struggling students.

---

## 🧠 Problem Statement

Educational institutions often struggle to identify students who are at risk of poor academic performance until it is too late. By using historical data such as study hours, attendance, internal scores, etc., we aim to:

* Predict final academic scores
* Classify students as *At Risk* or *Not At Risk*

---

## 🗂 Dataset Description

The dataset contains student-related academic features, including:

* Study-related metrics
* Attendance
* Internal assessments
* Final score (target for regression)
* At-risk label (target for classification)

The dataset also includes **missing values**, which were intentionally handled to demonstrate data-cleaning skills.

---

## 🔧 Tech Stack & Libraries Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib & Seaborn** – Data visualization (EDA)
* **Scikit-learn** – Machine Learning models and preprocessing

---

## 🔄 Machine Learning Pipeline

### 1️⃣ Data Cleaning

* Handled missing values using appropriate statistical methods
* Verified data consistency

### 2️⃣ Exploratory Data Analysis (EDA)

* Distribution plots
* Count plots for class balance
* Feature-wise analysis

### 3️⃣ Feature Engineering

* Feature selection
* Separation of input (X) and output (y)
* Scaling using **StandardScaler**

### 4️⃣ Model Building

Two types of ML models were implemented:

#### 🔹 Linear Regression

* Used to predict **Final Score**
* Evaluated using R² Score and Mean Squared Error

#### 🔹 Logistic Regression

* Used to predict **At-Risk status**
* Evaluated using Accuracy Score and Confusion Matrix

---

## 📊 Model Evaluation

* Regression metrics: R² Score, MSE
* Classification metrics: Accuracy, Confusion Matrix
* Train-test split used to avoid overfitting

---

## 📈 Results & Insights

* Attendance and study-related features strongly influence performance
* Logistic Regression successfully identifies at-risk students
* Scaling significantly improves model stability

---

## 🚀 Future Improvements

* Add advanced models (Random Forest, XGBoost)
* Perform hyperparameter tuning
* Add feature importance analysis
* Deploy as a web application (Streamlit / Flask)

---

## 📁 Project Structure

```
├── mlpro2.ipynb
├── README.md

```

---

## 👤 Author

**Aman Trivedi**
Aspiring Machine Learning Engineer | Python Developer

---

## ⭐ Final Note

This project demonstrates a solid foundation in Machine Learning concepts and practical implementation. It is suitable for showcasing on **GitHub**, **resumes**, and **ML portfolios**.
