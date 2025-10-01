---
layout: project
type: project
image: img/toastereats.jpg
title: "Breast Cancer Classification"
date: 2025
published: true
labels:
  - Python
summary: "Breast Cancer Classification with Logistic Regression and PCA."
---



## Overview
This project applies basic machine learning methods to the **Breast Cancer Wisconsin (Diagnostic) Dataset** from the UCI repository.  
The goal was to predict whether a tumor is **malignant** or **benign** based on cell nuclei measurements.

I used logistic regression with and without Principal Component Analysis (PCA) to evaluate how dimensionality reduction affects model performance.

---

## Dataset
- **Source:** [UCI Machine Learning Repository – Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))  
- **Size:** 569 samples × 30 numeric features  
- **Target:** Binary classification (Malignant = 1, Benign = 0)

---

## Methods
1. **Data Preprocessing**  
   - Standardized features (mean 0, unit variance)  
   - Stratified train/test split  

2. **Models**  
   - Logistic Regression (baseline, no dimensionality reduction)  
   - Logistic Regression after PCA (reduced to 2 components)  

3. **Evaluation**  
   - Accuracy on train and test sets  
   - Confusion matrix and classification report  
   - PCA scatter plot to visualize separation  

---

## Results
- **Without PCA:**  
  - Train Accuracy ≈ 0.99  
  - Test Accuracy ≈ 0.96  

- **With PCA (2 components):**  
  - Train Accuracy ≈ 0.96  
  - Test Accuracy ≈ 0.95  

> PCA reduced dimensionality while retaining most variance.  
> Logistic regression still performed well, but raw features gave slightly higher accuracy.

---

## Visualization
- PCA scatter plot shows malignant and benign samples forming distinct clusters.  
- Confusion matrices highlight that both approaches achieve high precision/recall.  

---

## Takeaways
- Even simple models like Logistic Regression can achieve high accuracy on structured biomedical data.  
- PCA is useful for visualization and dimensionality reduction, though it may slightly reduce accuracy.  
- This project reflects how **machine learning can support early cancer diagnosis**, and demonstrates my ability to apply scikit-learn workflows to biomedical datasets.

---

## Tech Stack
- Python  
- scikit-learn  
- NumPy, pandas, matplotlib  

---

## Repository
Full code and notebook: [GitHub Repo](https://github.com/kseekins/breast_cancer_classification)  
