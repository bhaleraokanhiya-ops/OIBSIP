# OIBSIP - Oasis Infobyte Internship Projects

This repository contains tasks completed as part of the **AICTE Oasis Infobyte Internship Program (OIB-SIP)**.

## Task 1: Iris Flower Classification

### Objective
Build a machine learning model to classify Iris flowers into three species — Setosa, Versicolor, and Virginica — based on sepal and petal measurements.

### Dataset
The classic Iris dataset (150 samples, 4 features: sepal length, sepal width, petal length, petal width), loaded via `sklearn.datasets`.

### Approach
1. Loaded and explored the dataset (EDA with pairplots, summary statistics)
2. Split data into training (80%) and test (20%) sets
3. Trained a **Decision Tree Classifier**
4. Evaluated performance using accuracy, classification report, and confusion matrix
5. Analyzed feature importance

### Results
- **Accuracy: 93.33%**
- Petal length and petal width were the most important features for classification
- Perfect classification on Setosa; minor confusion between Versicolor and Virginica (1 misclassification each)

### Files
- `Kanhaiya_Task1_Iris_Classification.ipynb` — full notebook with code, visualizations, and results

### Tech Stack
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn

---
**Intern:** Kanhaiya Bhalerao
**Program:** AICTE Oasis Infobyte Internship Program (OIBSIP)
