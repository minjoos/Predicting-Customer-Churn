# Supervised-Learning-Capstone-Project:Tree-Methods

Overview

This project aims to predict customer churn using various tree-based machine learning models. By leveraging a rich dataset, we explore multiple aspects of the data, perform detailed exploratory data analysis (EDA), and build predictive models to achieve accurate churn prediction.

Table of Contents

	1.	Introduction
	2.	Data Overview
	3.	Exploratory Data Analysis (EDA)
	4.	Predictive Modeling
	•	Decision Tree
	•	Random Forest
	•	Boosted Trees
	5.	Results and Insights
	6.	Conclusion

Introduction

Customer churn prediction is crucial for businesses to retain their customer base. In this project, we use tree-based methods to build models that predict whether a customer will churn based on various features.

Data Overview

The dataset consists of 7032 records with 21 features, including customer demographics, account information, and services subscribed. Key features include:

	•	tenure: Number of months the customer has been with the company
	•	MonthlyCharges: The amount charged to the customer monthly
	•	TotalCharges: The total amount charged to the customer

Exploratory Data Analysis (EDA)

EDA is conducted to understand the data distribution and relationships between features. Key steps include:

	•	Checking for null values and data types
	•	Visualizing distributions of numerical features
	•	Analyzing the correlation between features and the churn variable
	•	Creating box plots and violin plots to understand feature distributions across churn categories

Predictive Modeling

Decision Tree

	•	Model Training: A single decision tree is trained with optimal hyperparameters.
	•	Evaluation: Performance metrics include accuracy, precision, recall, and F1-score. A confusion matrix is plotted to visualize model performance.
	•	Feature Importance: The importance of each feature in the decision tree is calculated and visualized.

Random Forest

	•	Model Training: A random forest classifier with 100 estimators is used.
	•	Evaluation: Similar to the decision tree, performance metrics and a confusion matrix are generated.
	•	Feature Importance: The importance of features in the random forest model is analyzed.

Boosted Trees

	•	Model Training: An AdaBoost classifier is trained.
	•	Evaluation: Performance metrics and a confusion matrix are generated.
	•	Feature Importance: Feature importance is analyzed for the boosted trees model.

Results and Insights

	•	Performance Comparison: Among the models, the AdaBoost classifier showed the best performance with an accuracy of 83%.
	•	Feature Analysis: Features such as Contract, InternetService, and PaymentMethod showed significant importance in predicting churn.

Conclusion

Tree-based methods, particularly the AdaBoost classifier, are effective in predicting customer churn. The project highlights the importance of feature selection and model tuning in achieving high predictive accuracy.
