# Predictive Classification Using Random Forest Ensembles

## 1. Project Overview

This project focuses on building a machine learning classification model using the Random Forest algorithm to predict the presence of heart disease based on patient health-related features. The project includes data cleaning, exploratory data analysis, model training, and performance evaluation.

## 2. Objective

The main objective is to apply the Random Forest classification algorithm to a real-world dataset and evaluate its performance using different machine learning metrics and visualizations.

## 3. Dataset

- **Dataset Name:** Heart Failure Prediction Dataset
- **Source:** Kaggle
- **Dataset Link:** https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
- **Target Column:** `HeartDisease`
- **Target Values:** `0` – No heart disease; `1` – Heart disease

The dataset contains patient health information used to train and evaluate the classification model.

## 4. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Project Workflow

1. Import the required Python libraries.
2. Load and inspect the dataset.
3. Perform exploratory data analysis (EDA).
4. Visualize feature distributions and class imbalance.
5. Create a correlation heatmap.
6. Handle missing values and duplicate records.
7. Encode categorical features using One-Hot Encoding.
8. Split the dataset into training and testing sets in an 80:20 ratio.
9. Train the Random Forest classification model.
10. Evaluate the model using classification metrics.
11. Visualize the confusion matrix, ROC curve, and feature importance.

## 6. Algorithm Used

**Random Forest Classifier**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions. It can help improve prediction stability and reduce overfitting compared with relying on a single decision tree.

Model parameters used:
- `n_estimators = 100`
- `max_depth = 10`
- `random_state = 42`
- `class_weight = "balanced"`

## 7. Evaluation Metrics

The model is evaluated using the following metrics:

- **Accuracy:** Measures the overall proportion of correct predictions.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **Recall:** Measures how many actual positive cases are correctly identified.
- **F1-score:** Represents the balance between precision and recall.
- **ROC-AUC:** Measures the model's ability to distinguish between the two target classes.

## 8. Visualizations

The project includes the following visualizations:

- Feature distribution plots
- Target class distribution
- Correlation heatmap
- Confusion matrix heatmap
- ROC curve
- Feature-importance bar chart

These visualizations help understand the dataset, evaluate model performance, and identify features that contribute to the model's predictions.

## 9. Conclusion

This project demonstrates the use of the Random Forest algorithm for a binary classification problem. Data preprocessing, exploratory analysis, model training, and evaluation help assess how well the model predicts the target class. The project can be improved further through hyperparameter tuning, cross-validation, and comparison with other classification algorithms such as Gradient Boosting.

## 10. Disclaimer

This project is developed for educational purposes only. The model is not intended for medical diagnosis or clinical decision-making.
