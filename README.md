# Predictive Analysis of Breast Cancer Survival Using Clinical and Tumor Attributes

## Project Overview
This project focuses on predicting **breast cancer survival status** using clinical, biological, and tumor-related attributes. The goal was to identify key factors influencing survival outcomes and to evaluate multiple machine learning models to determine the most effective predictive approach.

The analysis uses a publicly available **breast cancer dataset from Kaggle** and applies data preprocessing, statistical testing, feature analysis, and supervised machine learning techniques.

---

## Objectives
- Identify clinical and biological factors associated with breast cancer survival
- Evaluate the impact of tumor characteristics and hormonal status on survival outcomes
- Build and compare multiple classification models
- Select the best-performing model based on accuracy and ROC–AUC

---

## Dataset
- **Source:** Kaggle – Breast Cancer Dataset
- **Type:** Structured clinical data
- **Features:** 16 clinical and biological attributes
- **Target Variable:** Survival Status (Alive / Dead)

Key features include:
- Tumor size, tumor grade, cancer stage
- Lymph node involvement
- Estrogen and progesterone status
- Age and regional node information

---

## Data Preprocessing
- Verified absence of missing values
- Encoded categorical variables into numerical format
- Performed exploratory data analysis (EDA)
- Visualized feature relationships using histograms, boxplots, violin plots, and heatmaps

---

## Statistical Analysis
- **Shapiro–Wilk Test** for normality assessment
- **Chi-Square Test** to evaluate relationships between categorical variables and survival
- **Kendall Tau Correlation** for non-parametric association analysis

Results showed significant associations between survival and:
- Disease stage
- Hormone receptor status (Estrogen & Progesterone)
- Lymph node involvement

---

## Machine Learning Models
The following classification models were implemented and compared:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

## Model Evaluation
- Train–test split: 80/20
- Metrics used:
  - Accuracy
  - Precision, Recall, F1-Score
  - ROC–AUC

## Best Performing Model
- **Logistic Regression**
- **Accuracy:** ~84.6%
- **ROC–AUC:** ~0.72

---

## Key Insights
- Hormonal status and disease stage play a major role in survival outcomes
- Logistic Regression provided the best balance of performance and interpretability
- Feature importance analysis highlighted survival months, tumor size, and node involvement as key predictors

---

## Tools & Technologies
- **Python**
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

---

## Repository Contents
- **Notebook:** End-to-end data preprocessing, analysis, modeling, and evaluation
- **Presentation:** Summary of methodology, results, and conclusions

---

## Key Takeaway
This project demonstrates how machine learning and statistical analysis can be applied to real-world healthcare data to support clinical insight generation and outcome prediction.

---
