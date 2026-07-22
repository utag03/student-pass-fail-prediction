# Student Pass/Fail Prediction

Binary classification model predicting whether a student 
will pass or fail based on study habits and academic history,
using Logistic Regression with Python and Scikit-learn.

## 📊 Project Overview
Analyzed 30 student records with 3 key features to build
a classification model that predicts student outcomes
with 100% accuracy on test data.

## 🎯 Problem Statement
Can we predict whether a student will pass or fail based on:
- Study hours per day
- Attendance percentage  
- Previous exam score

## 🏆 Results
- **Accuracy: 100%**
- **False Negatives: 0** (no passing student predicted as failing)
- **False Positives: 0** (no failing student predicted as passing)

## 🔍 Key Findings
- Students with study_hours < 3, attendance < 55% 
  and prev_score < 40 have near 0% chance of passing
- Students with study_hours > 8, attendance > 90% 
  and prev_score > 85 have near 100% chance of passing
- Logistic Regression outperformed expectations on this dataset
  due to clear linear separability between Pass and Fail groups

## 📈 What's Inside the Notebook
1. Exploratory Data Analysis
2. Feature selection and train/test split (80/20)
3. Logistic Regression model training
4. Model evaluation — Accuracy, Classification Report
5. Confusion Matrix visualization
6. Predicting new students with probability scores
7. Sigmoid function visualization — understanding HOW 
   the model makes decisions

## 🧠 Concepts Covered
- Classification vs Regression
- Logistic Regression and the Sigmoid function
- Confusion Matrix (TP, TN, FP, FN)
- Precision, Recall and F1 Score
- Probability thresholds for binary classification

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Lab
