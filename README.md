# Predictive Maintenance System for Machines ⚙️

This project implements a **Predictive Maintenance System** to predict **machine failure** using Machine Learning.  
An **SVM classifier** is optimized using a **Genetic Algorithm (GA)** to improve prediction accuracy.

---

## Project Overview
- Objective: Predict whether a machine will **fail or not**
- Approach:
  - Use selected sensor features
  - Optimize SVM hyperparameters (`C`, `gamma`) using Genetic Algorithm
- Output:
  - Machine Failure (1)
  - No Failure (0)

---

## Features Used
The model uses the following machine sensor parameters:
- Air temperature [K]
- Process temperature [K]
- Rotational speed [rpm]
- Torque [Nm]
- Tool wear [min]

---

## Machine Learning Techniques
- Support Vector Machine (SVM) – RBF kernel
- Genetic Algorithm for hyperparameter tuning
- Feature scaling using StandardScaler

---

## Model Performance
- Test Accuracy: **~98.15%**
- Training Accuracy: **~98.9%**
- Confusion Matrix and Classification Report used for evaluation
- GA convergence curve plotted for optimization analysis

---

## Dataset
- File: `soft dataset.csv`
- Target column: `Machine failure`
- Binary classification (0 = No Failure, 1 = Failure)

---

## Visualizations
- GA Convergence Curve
- Training vs Testing Accuracy Bar Chart
- Confusion Matrix

---

## Manual Testing
The system supports manual test samples to predict machine failure status using trained model.

---

## Technologies Used
- Python
- pandas, numpy
- scikit-learn
- matplotlib
