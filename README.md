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
## Task 2: Unemployment Analysis with Python

### Objective
Analyze the unemployment rate in India, with a focus on the impact of the COVID-19 lockdown period, using real-world labor market data.

### Dataset
`Unemployment_Rate_upto_11_2020.csv` — state-wise unemployment rate, employment figures, and labour participation rate across India (Jan–Oct 2020), 267 records.

### Approach
1. Loaded and cleaned the dataset (checked for nulls, converted dates)
2. Visualized unemployment rate trends across all states over time
3. Highlighted the COVID-19 lockdown period (Mar–May 2020) against the national average trend
4. Identified the top 10 most-affected states by average unemployment rate
5. Compared rural vs. urban unemployment patterns

### Key Insights
- Unemployment rates spiked sharply in April–May 2020, coinciding with the COVID-19 lockdown
- States like Delhi, Puducherry, and Jammu & Kashmir recorded the highest average unemployment rates in this period
- Clear regional disparities in how badly different states were affected

### Files
- `Kanhaiya_Task2_Unemployment_Analysis.ipynb` — full notebook with code, visualizations, and insights

### Tech Stack
Python, pandas, NumPy, matplotlib, seaborn
## Task 3: Car Price Prediction with Machine Learning

### Objective
Build a machine learning model to predict the selling price of cars based on their features (engine size, horsepower, dimensions, fuel type, etc.).

### Dataset
`CarPrice.csv` — 205 car records with 26 features including engine specs, dimensions, fuel type, and price.

### Approach
1. Loaded and explored the dataset (no missing values)
2. Dropped non-predictive columns (car ID, car name)
3. Label-encoded categorical features (fuel type, car body, drive wheel, etc.)
4. Visualized feature correlations via heatmap
5. Trained a **Random Forest Regressor**
6. Evaluated using R² score and RMSE
7. Analyzed feature importance

### Results
- **R² Score: 0.9579** (model explains ~95.8% of price variance)
- **RMSE: 1823.91**
- Engine size and curb weight were the most influential features in predicting price
- Actual vs. Predicted plot shows strong alignment with minimal deviation

### Files
- `Kanhaiya_Task3_Car_Price_Prediction.ipynb` — full notebook with code, visualizations, and results

### Tech Stack
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn
