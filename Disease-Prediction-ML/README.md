# 🩺 Disease Prediction from Medical Data

## CodeAlpha Machine Learning Internship — Task 4

A machine learning classification project that predicts whether a breast tumor is **benign or malignant** using medical diagnostic measurements.

The project implements and compares multiple machine learning algorithms to determine their performance on structured medical data.

---

## 📌 Project Overview

Disease prediction is an important application of machine learning in healthcare. This project demonstrates how supervised classification algorithms can be applied to medical diagnostic data to classify tumor cases into two categories:

- **Benign**
- **Malignant**

The project focuses on data preprocessing, exploratory data analysis, model training, evaluation, comparison, and prediction.

> ⚠️ **Disclaimer:** This project is intended for educational and machine-learning demonstration purposes only. It is not a medical diagnostic tool and should not be used for clinical decision-making.

---

## 🎯 Objective

The main objective of this project is to:

- Analyze structured medical data.
- Preprocess the dataset for machine learning.
- Apply classification algorithms.
- Compare different machine learning models.
- Evaluate model performance using multiple metrics.
- Select the best-performing model.
- Save the trained model for future use.

---

## 📊 Dataset

This project uses the **Breast Cancer Wisconsin Diagnostic Dataset** available through Scikit-learn.

### Dataset Details

- **Total records:** 569
- **Medical features:** 30
- **Target classes:** 2

### Target Classes

| Value | Diagnosis |
|---:|---|
| 0 | Benign |
| 1 | Malignant |

---

## 🔬 Medical Features

The dataset contains numerical diagnostic measurements such as:

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Mean Concave Points
- Mean Symmetry
- Mean Fractal Dimension
- Radius Error
- Texture Error
- Perimeter Error
- Area Error
- Smoothness Error
- Compactness Error
- Concavity Error
- Concave Points Error
- Symmetry Error
- Fractal Dimension Error
- Worst Radius
- Worst Texture
- Worst Perimeter
- Worst Area
- Worst Smoothness
- Worst Compactness
- Worst Concavity
- Worst Concave Points
- Worst Symmetry
- Worst Fractal Dimension

---

## 🤖 Machine Learning Algorithms

Four classification algorithms were implemented and compared:

### 1. Logistic Regression

A linear classification algorithm used as a strong baseline model for binary classification.

### 2. Support Vector Machine (SVM)

A supervised learning algorithm that finds an optimal decision boundary between classes.

### 3. Random Forest

An ensemble learning algorithm that combines multiple decision trees to improve classification performance.

### 4. XGBoost

A powerful gradient boosting algorithm designed for efficient and accurate classification and regression tasks.

---

## ⚙️ Project Workflow

```text
Medical Dataset
       ↓
Data Loading
       ↓
Data Exploration
       ↓
Missing Value Checking
       ↓
Exploratory Data Analysis
       ↓
Train-Test Split
       ↓
Feature Scaling
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Model Comparison
       ↓
Best Model Selection
       ↓
Disease Prediction
       ↓
Model Saving