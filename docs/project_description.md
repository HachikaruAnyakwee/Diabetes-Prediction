# Diabetes Prediction Project

## **Introduction**
Diabetes is a global health challenge that affects millions of people. This project aims to predict diabetes using machine learning models. The goal is to analyze the performance of various algorithms and determine the most effective one for this problem.

### **Project Objectives**
- Explore and preprocess the diabetes dataset.
- Train and evaluate machine learning models:
    - Generalized Linear Model (GLM)
    - Decision Tree
    - Random Forest
    - Logistic Regression
- Compare model performances using metrics like accuracy, precision, recall, and F1-score.

## **Dataset**
The dataset was sourced from [Kaggle](https://www.kaggle.com/code/omeraydogddu/diabetes-dataset-feature-engineering-eda/input). It contains health metrics (e.g., glucose levels, BMI) and a binary outcome variable indicating whether a person has diabetes.

### **Dataset Overview**
- **Rows**: 768
- **Columns**: 9
- **Target Variable**: `Outcome` (0 = No diabetes, 1 = Diabetes)

| Feature                     | Description                                |
|-----------------------------|--------------------------------------------|
| Pregnancies                 | Number of pregnancies                      |
| Glucose                     | Plasma glucose concentration               |
| BloodPressure               | Diastolic blood pressure (mm Hg)           |
| SkinThickness               | Triceps skinfold thickness (mm)            |
| Insulin                     | 2-hour serum insulin (mu U/ml)             |
| BMI                         | Body Mass Index                            |
| DiabetesPedigreeFunction    | Diabetes pedigree function                 |
| Age                         | Age of the patient                         |
| Outcome                     | 0 or 1 (Diabetes or No Diabetes)           |

### **Why This Project Matters**
Early detection of diabetes can save lives and reduce healthcare costs. Machine learning provides a way to build predictive tools that help identify high-risk individuals and allow for timely interventions.

---

## **Steps Taken**

### 1. **Data Exploration and Cleaning**
- Loaded the dataset and checked for missing values and incorrect entries.
- Replaced missing or zero values in key columns (e.g., `Glucose`, `BloodPressure`) with the median.
- Split the dataset into training and testing sets.

### 2. **Model Training**
We used four different machine learning models:
1. **Generalized Linear Model (GLM)**
2. **Decision Tree**
3. **Random Forest**
4. **Logistic Regression**

Each model was trained and evaluated on the same dataset.

### 3. **Model Comparison**
The performance of the models was compared using:
- Accuracy
- Precision
- Recall
- F1-Score

### 4. **Visualization**
Created charts to compare the results and identify the best-performing model.

---

## **Results**

| Model                 | Accuracy | Recall   | F1-Score |
|-----------------------|----------|----------|----------|
| **GLM** | 75.32%   | 61.82%   | 64.15%   |
| **Decision Tree** | 79.22%   | 87.27%   | 75.00%   |
| **Random Forest** | 94.81%   | 89.09%   | 92.45%   |
| **Logistic Regression**| 77.27%   | 61.82%   | 66.02%   |

- The **Random Forest** model performed the best, with an accuracy of 94.81%.
- The **Decision Tree** model was a close second, with an accuracy of 79.22%.
- The GLM and Logistic Regression models had lower accuracies, but they provided insights into feature importance.

---

## **Next Steps**
- Improve data preprocessing (e.g., feature engineering).
- Test additional machine learning algorithms, such as Support Vector Machines (SVM).
- Deploy the best model using a web app (e.g., Streamlit or Flask).

---
