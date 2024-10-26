Diabetes Prediction Model Documentation

Introduction
This project focuses on analyzing diabetes data using various predictive models in Python. The dataset contains information about individuals diagnosed with diabetes, including demographic attributes, medical history, and clinical measurements. The goal is to predict whether a person has diabetes or not using NB and logistic regression .

Dataset Features
1- Pregnancies: Number of pregnancies.
2- Glucose: Blood glucose level.
3- Blood Pressure: Blood pressure measurement.
4- Skin Thickness: Skin thickness.
5- Insulin: Blood insulin level.
6- BMI: Body Mass Index (BMI).
7- Diabetes Pedigree Function: Percentage of likelihood for diabetes based on family history.
8- Age: Age of the individual
9- Outcome: Final result (1 = Yes, 0 = No).

Problem Statement
The problem is to predict whether a person has diabetes using these different features. This prediction is important to help doctors make data-driven decisions to identify patients at risk.

Libraries Used
•	pandas: For loading, cleaning, and analyzing data.
•	NumPy: For mathematical operations.
•	seaborn: For creating visualizations.
•	sklearn: For building and evaluating machine learning models.

Machine Learning Models
•	Logistic Regression: Suitable for binary classification.
•	Gaussian Naive Bayes: Naive Bayes model.

Data Loading and Preprocessing
The data was loaded using pandas.read_csv() and analyzed using the following methods:

•	data.head(): To display the first five rows of the dataset.
•	data.info(): To get information about the columns.
•	data.describe(): To provide a statistical description of the dataset.
•	data.corr(): To analyze the correlation between different features.

Model Evaluation
The models were evaluated using the following metrics:
•	Accuracy: The percentage of correct predictions.
•	Confusion Matrix: To determine the accuracy for each class.
•	Classification Report: Provides detailed information on precision, recall, and F1-score.

