# Diabetes Prediction Project

## **Introduction**
This project explores predictive modeling for diabetes using multiple machine learning algorithms, including:
- **Generalized Linear Model (GLM)**
- **Decision Tree**
- **Random Forest**
- **Logistic Regression**

We evaluate the models using various performance metrics, such as:
- **Accuracy**
- **F1-Score**
- **Recall**
- **Precision**
- **Confusion Matrix**

The study aims to provide insights into the best-suited algorithm for diabetes prediction, with a focus on improving early detection and healthcare outcomes.

## **Dataset**
- **Source:** [Diabetes Dataset - Kaggle](https://www.kaggle.com/code/omeraydogddu/diabetes-dataset-feature-engineering-eda/input)
- **Description:** The dataset contains health-related metrics (e.g., glucose levels, BMI) and a binary outcome variable indicating diabetes status.
- **Target Variable**: `Outcome` (0 = No diabetes, 1 = Diabetes)

## **Project Objectives**
1. Address limitations of previous diabetes prediction approaches by testing diverse machine learning algorithms.
2. Use comparative analysis to determine the most effective predictive model.
3. Aid healthcare professionals in risk stratification for better resource allocation.

## **Project Structure**

| Directory/File          | Description                                    |
|--------------------------|------------------------------------------------|
| `README.md`             | Overview of the project                        |
| `requirements.txt`      | Project dependencies                           |
| `.gitignore`            | Files and directories to ignore by Git        |
| `LICENSE`               | Project license                                |
| `src/`                  | Source code directory                          |
| `src/data_preparation.py`| Script for data preprocessing and preparation |
| `src/model_analysis.py`   | Script for GLM, DT, RF, LR model analysis    |
| `Dataset/`                 | Directory for the dataset                      |
| `docs/`                 | Directory for additional documentation         |
| `docs/project_description.md` | Detailed project description               |
| `docs/model_explanations.md` | Model explanations and insights              |


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

## **Models and Performance**
| Model                  | Accuracy | Recall  | F1-Score |
|------------------------|---------|---------|----------|
| **GLM**               | 75.32%  | 61.82%  | 64.15%   |
| **Decision Tree**      | 79.22%  | 87.27%  | 75.00%   |
| **Random Forest**      | 94.81%  | 89.09%  | 92.45%   |
| **Logistic Regression**| 77.27%  | 61.82%  | 66.02%   |

**Key Findings:**
- **Random Forest** achieved the highest accuracy (94.81%) and F1-score (92.45%).
- **Decision Tree** had the highest recall (87.27%), making it effective for minimizing false negatives.
- **GLM and Logistic Regression** performed similarly, with moderate accuracy and recall.
## **Contributors**
Hachikaru Anyakwee ([GitHub Profile](https://github.com/HachikaruAnyakwee))

## **License**
This project is licensed under the MIT License. See the LICENSE (https://github.com/HachikaruAnyakwee/diabetes-prediction/edit/main/README.md#:~:text=t-,LICENSE,-README.md) file for details.4
