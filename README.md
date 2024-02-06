# Vehicle-Classification
## Vehicle Classification Project
Overview
Welcome to my Vehicle Classification project! In this project, I've developed a machine learning model to classify vehicles into different classes based on various features. The dataset includes columns such as 'buying', 'maint', 'doors', 'persons', 'lug_boot', 'safety', and the target column 'class', which represents four different vehicle classes.

### Project Highlights
Data Analysis and Exploration
Conducted thorough data analysis and exploration to understand the dataset.
Observed a perfectly balanced dataset, but the target column ('class') exhibited significant imbalance.
Utilized the Synthetic Minority Over-sampling Technique (SMOTE) to address the class imbalance.
## Machine Learning Models
Implemented three powerful machine learning models:

### XGBoost
Achieved an impressive testing accuracy of 93.4%.
### ExtraTrees
Demonstrated strong performance with a testing accuracy of 93%.
### AdaBoost with Random Forest as Base Estimator
Delivered a commendable testing accuracy of 92.5%.
Evaluation Metrics
Provided comprehensive evaluation metrics for all models, including:
Precision
Recall
F1 Score
Classification Report
Confusion Matrix
ROC AUC Curve
Accuracy Comparison Graph
Visualized the performance of all models with an accuracy comparison graph.
Highlighted XGBoost as the top-performing model with a testing accuracy of 93.4%.

## Project Structure
Data Analysis.ipynb

Detailed analysis of the dataset.
Addressed class imbalance using SMOTE.
Machine_Learning_Models.ipynb

Implemented XGBoost, ExtraTrees, and AdaBoost models.
Evaluated and compared the performance of each model.
Evaluation_Metrics.ipynb

Provided in-depth evaluation metrics for all models.
Accuracy_Comparison_Graph.ipynb

Visualized the accuracy comparison among all models.

## How to Use
Clone the repository.
Run the Jupyter notebooks in the specified order to replicate the analysis and model development.
Explore the accuracy comparison graph to identify the top-performing model.
