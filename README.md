# Diabetes Prediction Project

## **Introduction**
This project explores predictive modeling for diabetes using multiple machine learning algorithms, including:
- **Generalized Linear Model (GLM)**
- **Decision Tree**
- **Random Forest**
- **Logistic Regression**

We evaluate the models using various performance metrics, such as:
- **Accuracy**
- **ROC Score**
- **R² Score**
- **Mean Squared Error (MSE)**

The study aims to provide insights into the best-suited algorithm for diabetes prediction, with a focus on improving early detection and healthcare outcomes.

## **Dataset**
- **Source:** [Diabetes Dataset - Kaggle](https://www.kaggle.com/code/omeraydogddu/diabetes-dataset-feature-engineering-eda/input)
- **Description:** The dataset contains health-related metrics (e.g., glucose levels, BMI) and a binary outcome variable indicating diabetes status.

## **Project Objectives**
1. Address limitations of previous diabetes prediction approaches by testing diverse machine learning algorithms.
2. Use comparative analysis to determine the most effective predictive model.
3. Aid healthcare professionals in risk stratification for better resource allocation.

## **Project Structure**
diabetes-prediction/
│ ├── README.md # Overview of the project
│ ├── requirements.txt # Dependencies
│ ├── .gitignore # Ignored files
│ ├── LICENSE # License
│ ├── src/ # Source code
│ │ ├── data_preparation.py
│ │ ├── glm_analysis.py
│ │ ├── decision_tree.py
│ │ ├── random_forest.py
│ │ └── logistic_regression.py
│ ├── data/ # Dataset
│ ├── results/ # Output files, graphs, evaluations
│ ├── notebooks/ # Jupyter notebooks (optional)
│ └── docs/ #Additional documentation
│   ├── project_description.md # Detailed Project Description
│   └── model_explanations.md # Model Explanations


## **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/HachikaruAnyakwee/diabetes-prediction.git
   cd diabetes-prediction

2. Create a virtual environment:
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies:
   pip install -r requirements.txt

## **Usage**
1. Run the analysis scripts:
   python src/glm_analysis.py
   python src/decision_tree.py
   python src/random_forest.py
   python src/logistic_regression.py

2. View results in the results/ directory.

## **Results**
Model Comparison: Comparative analysis shows that the Random Forest model performed the best with the highest accuracy and balanced precision-recall.
Performance Metrics:
GLM: Accuracy 75.32%
Decision Tree: Accuracy 85.71%
Random Forest: Accuracy 92.21%
Logistic Regression: Accuracy 78.57%

## **Contributors**
Hachikaru Anyakwee ([GitHub Profile](https://github.com/HachikaruAnyakwee))

## **License**
This project is licensed under the MIT License. See the LICENSE (https://github.com/HachikaruAnyakwee/Diabetes-Prediction-Project/edit/main/README.md#:~:text=t-,LICENSE,-README.md) file for details.4
