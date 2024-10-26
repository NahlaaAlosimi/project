Retail Store Data Analysis Project

Introduction
Objective:
This project outlines the steps taken for data preprocessing, model training, and market basket analysis using multiple datasets from a retail store. The main goals are:
1.	Predicting which products will be reordered.
2.	Discovering association rules between items frequently bought together.
Logistic Regression was used for prediction, and the Apriori Algorithm was employed for market basket analysis.
 Datasets Used:
•	Departments: Information about product departments.
•	Order Products (Train & Prior): Details of products ordered in the training and prior datasets.
•	Orders: Data about customer orders.
•	Products: Product details.
•	Aisles: Information about product aisles.

Data Loading and Cleaning
Multiple CSV files containing order and product data were loaded using pandas and merged to create a comprehensive view of the orders and products.
Data Exploration and Cleaning:
•	The training dataset was created by merging orders labeled as "train" with the training order products data.
•	Missing values were checked and cleaned. For instance, missing values in the days_since_prior_order column were replaced with the median.




Additional Features:
Extra features were added such as:
•	The number of times a product was bought by a user.
•	The number of unique users who bought a product.

Data Preparation and Feature Engineering
Preparing the Data for the Model:
•	Columns that are not useful for the model, such as order_id, user_id, and product_id, were dropped.
•	The target variable (reordered) was separated from the training data.

Handling Outliers
Outliers can affect the performance of machine learning models. They were detected and handled using the Interquartile Range (IQR) method.

Model Training and Evaluation Using Logistic Regression
Data Splitting:
The data was split into training (x_train, y_train) and testing sets (x_test) after being cleaned.
Handling Missing Values:
Rows with missing values in y_train were removed before training the model.
Logistic Regression Model Training:
The logistic regression model was trained on the cleaned training data and used to predict on both the training and testing sets.
Model Evaluation:
The following metrics were used to evaluate the model's performance:
•	Accuracy, Precision, Recall, and F1-Score.

