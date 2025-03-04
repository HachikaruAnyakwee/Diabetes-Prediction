# Machine Learning Models: Summaries and Explanations

This document provides an overview of the machine learning models used in the Diabetes Prediction Project.

---

## **1. Generalized Linear Model (GLM)**

### **Overview**
The Generalized Linear Model (GLM) is an extension of linear regression that allows the dependent variable to follow a non-normal distribution. In this project, we used the **logistic regression variant** of GLM, which predicts a binary outcome (diabetes or no diabetes).

### **How It Works**
- GLM uses a logistic function to predict probabilities.
- The model outputs probabilities, which are converted to binary outcomes (0 or 1) using a threshold (e.g., 0.5).

### **Results**
- **Accuracy**: 75.32%
- GLM provided insights into how features like glucose and BMI contribute to diabetes risk.

---

## **2. Decision Tree**

### **Overview**
A Decision Tree is a flowchart-like structure that splits data into branches based on feature values. It is intuitive and easy to understand.

### **How It Works**
- The tree starts at a root node (e.g., `Glucose` level).
- At each step, it splits the data into branches based on a feature and a decision rule (e.g., `Glucose > 100`).
- The process continues until the tree reaches a stopping condition (e.g., a maximum depth or no further splits are possible).

### **Results**
- **Accuracy**: 85.71%
- The Decision Tree was easy to interpret but prone to overfitting.

---

## **3. Random Forest**

### **Overview**
The Random Forest is an ensemble model that combines multiple Decision Trees to improve accuracy and reduce overfitting.

### **How It Works**
- Trains multiple Decision Trees on random subsets of the data.
- Combines their predictions using a majority vote (for classification).

### **Results**
- **Accuracy**: 92.21%
- The Random Forest outperformed all other models and showed balanced precision and recall.

---

## **4. Logistic Regression**

### **Overview**
Logistic Regression is a simple and widely used algorithm for binary classification. It estimates the probability of the target class using a logistic function.

### **How It Works**
- Each feature is assigned a weight (coefficient) that represents its influence on the outcome.
- The logistic function maps the weighted sum of features to a probability.

### **Results**
- **Accuracy**: 78.57%
- While not the most accurate, Logistic Regression provided a clear understanding of feature importance.

---

## **Feature Importance**

Some features had a significant impact across multiple models:
- **Glucose**: Strongly correlated with diabetes.
- **BMI**: Indicates the level of body fat and its relation to diabetes risk.
- **Age**: Older individuals were at higher risk.
- **Diabetes Pedigree Function**: Captures the likelihood of diabetes based on family history.

---

## **Conclusion**
- The Random Forest model is the best choice for diabetes prediction due to its high accuracy and ability to handle complex data.
- Simpler models like Logistic Regression and GLM are useful for understanding feature importance but less accurate.

---

## **Future Work**
- Experiment with advanced models like Gradient Boosting or XGBoost.
- Improve interpretability by visualizing tree structures or feature importance scores.
- Deploy the best model in a web application for real-world use.
