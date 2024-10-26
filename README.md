Data Analysis READM


INTRODCTION : Our project is based on data analysis and is divided into three separate sections, each focusing on a specific method for data analysis. However, each section is interconnected in some way with the others. In this README, I will include all the machine learning techniques used across the different codes. 

Project Beneficiary : 
-	One of the most important things learned is how to develop accurate forecasting models that can be used to improve data management, and we also discovered that logistic regression is considered the best model compared to Bez because of its higher accuracy in classification.
-	We also took advantage of the apriori algorithm, which reveals links between products purchased together and also helps us search for duplicate groups.
-	We recommend using more advanced models such as Random Forests and Gradient Boosting to improve prediction accuracy, indicating the potential for further performance improvements.
-	We also used the VIF indicator to check the linear multiplicity between the features to avoid their effect on the interpretation of the model and its effectiveness.
-	We also used logistic regression to enable the model to be trained and tested on unseen data.
-	We leveraged the Bagwords Count Vectorizer app to convert text into digital formats, allowing models to process message content as learnable data.





Diabetes Prediction

Objective: Predict whether a person has diabetes using various machine learning models.

Dataset :
Contains features such as the number of pregnancies, glucose level, blood pressure, skin thickness, insulin, BMI, diabetes pedigree, age, and the outcome (1 for diabetes, 0 for no diabetes).

Models Used :
-	Logistic Regression
-	Naive Bayes
-	Matrics 
-	

Tools :
Python libraries like Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

Key Results : 
The most accurate model was Logistic Regression.










Market Basket Analysis 

Objective:
Predict products that will be reordered and discover associations between items bought together.

Dataset:
Multiple datasets from a retail store containing product details, departments, orders, and aisles.

Models Used:
-	Logistic Regression for prediction.
-	Apriori Algorithm for market basket analysis.
-	Matrics 

Steps:
1 - Data Cleaning and Exploration.
2 - Logistic Regression model to predict reorders.
3 - Applying the Apriori Algorithm to extract association rules between products.

Key Results:
Prediction was effective, but there’s room for improvement using more advanced models.
Association analysis revealed strong relationships between products that can be used for targeted promotions.





Email Spam Classification 

Objective:  Classify emails as "spam" or "not spam" using machine learning models.

Dataset:
A dataset containing email content and spam classification (spam or not spam).

Models Used:
-	Logistic Regression
-	WordCloud
-	Multinomial NB
-	classification_repor
-	confusion_matrix

Steps:

1 - Text Processing: Includes tokenization, removing stopwords, and punctuation.
2 - Feature Extraction: Using CountVectorizer 
3 - Data Split: Dividing data into training and testing sets.
4 - Model Training and Evaluation: Evaluating models using accuracy, recall, and F1-score metrics.

Key Results:
Logistic Regression performed better than Naive Bayes





