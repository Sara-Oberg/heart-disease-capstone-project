# Heart-Disease Capstone Project
A machine learning project to explore and predict heart disease using patient health records. This project includes exploratory data analysis (EDA), data cleaning, feature engineering, and a baseline classification model to identify individuals at risk of heart disease.


# Research Question:
Can we predict heart disease in people regarding their basic personal and health information?

# Expected Data Source:
The data will come from a dataset "https://www.kaggle.com/datasets/mirzahasnine/heart-disease-dataset?select=heart_disease.csv" called heart_disease.csv, which includes basic personal and health information, provided as a CSV file.

# Techniques:

- Simple data analysis to understand the data
- Creating useful features from the data
- Using machine learning methods like Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting
- Checking how well the model works using methods like cross-validation, confusion matrix, and ROC curve

# Expected Results:
I aim to create a reliable tool that can predict who might develop heart disease based on their basic personal and health details. This tool will show us which factors are most important for predicting heart disease, helping doctors and patients take action early.

# Why This Question is Important:
Heart disease is a major cause of death around the world. If we can predict heart disease early, we can help people make lifestyle changes or get medical treatment sooner. Without answering this question, people might not know they are at risk, missing the chance to prevent serious health issues. 
A simple predictive tool can help doctors and patients make better decisions, saving lives and reducing healthcare costs by allowing earlier treatment and better personal care plans.

# 2. The insights based on the dataset heart_disease.csv

# The numbers of rows and columns:
Rows: 4238
Columns: 16

# Using df.info(), the types of each column can be find as follows: 

![info](https://github.com/user-attachments/assets/9655bb02-afb2-413b-b69c-39c0d478c386)


# These columns contain missing values:
| Column	    | Missing Values |
| ---------   | -------------- |
| education	  | 105 |
| cigsPerDay	| 29 |
| BPMeds	    | 53 |
| totChol	    | 50 |
| BMI		      | 19 |
| heartRate	  | 1 |
| glucose	    | 388 |

# Basic statistics (mean, min, max) for numeric columns:

| Feature	    | Mean	  | Min	  | Max
| age		      | 49.58	  | 32	  | 70
| cigsPerDay	| 9.00	  | 0	    | 70
| totChol	    | 236.72	| 107	  | 696
| sysBP		    | 132.35	| 83.5	| 295
| diaBP		    | 82.89	  | 48	  | 142.5
| BMI		      | 25.80	  | 15.54	| 56.8
| heartRate	  | 75.88	  | 44	  | 143
| glucose	    | 81.97	  | 40	  | 394

# There are no duplicates:
Number of duplicate rows: 0

# The numbers of categories of object-type columns

| Column		      | Unique Categories
| Gender	        | 2 		(Male, Female)
| education		    | 4 (graduate, postgraduate, etc.)
| prevalentStroke	| 2 (yes, no)
| Heart_ stroke		| 2 (yes, No)

# 3. Data Cleaning.

In this step, I did:
- Standardizes column names
- Fills missing numeric values with median (robust to outliers)
- Fills missing categorical values with the most common category
- Converts all string categories to lowercase for consistency




