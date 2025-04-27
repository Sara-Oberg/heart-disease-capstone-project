# Heart Disease and Stroke Prediction Using Machine Learning

**Author:** Sara Obergassel

# Executive Summary

This project explores the use of machine learning to predict the risk of heart disease or stroke based on demographic and clinical health features. Using real-world medical data, the goal is to build a predictive model that can help identify individuals at higher risk and contribute to earlier interventions, improving health outcomes. Logistic Regression was used as the baseline model, achieving an accuracy of approximately 85.19%.

# Change of Project

Originally, the proposed project focused on machine learning-based optimization of transistor sizing for analog circuit performance. However, due to the difficulty of obtaining a suitable dataset and the practical challenges of generating reliable LTspice simulation data within the project timeline, the project scope was changed.

The new project focuses on heart disease and stroke prediction using real-world medical data. This topic is both impactful to public health and better aligned with available datasets, allowing for meaningful exploration of machine learning techniques in a healthcare context.

The new project uses the "Heart Disease" dataset from Kaggle and aims to build a predictive model that can help identify individuals at higher risk of heart disease or stroke, potentially contributing to earlier intervention and prevention efforts.


# Heart-Disease Capstone Project
This project aims to explore and model health-related risk factors to predict whether an individual is likely to experience heart disease or stroke. The model is developed as part of a machine learning capstone project at UC Berkeley Haas School of Business, using real-world medical data.


# Research Question:
Can we predict heart disease in people regarding their basic personal and health information?

# Expected Data Source:
The data will come from a dataset "https://www.kaggle.com/datasets/mirzahasnine/heart-disease-dataset?select=heart_disease.csv" called heart_disease.csv, which includes basic personal and health information, provided as a CSV file.

# Expected Results:
I aim to create a reliable tool that can predict who might develop heart disease based on their basic personal and health details. This tool will show us which factors are most important for predicting heart disease, helping doctors and patients take action early.

# Why This Question is Important:
Heart disease is a major cause of death around the world. If we can predict heart disease early, we can help people make lifestyle changes or get medical treatment sooner. Without answering this question, people might not know they are at risk, missing the chance to prevent serious health issues. 
A simple predictive tool can help doctors and patients make better decisions, saving lives and reducing healthcare costs by allowing earlier treatment and better personal care plans.

# Methodology

- Data cleaning (handling missing values, outlier analysis, feature engineering)
- Exploratory Data Analysis (EDA) to understand distributions and relationships
- Encoding of categorical variables and feature scaling
- Baseline classification model using Logistic Regression
- Model evaluation using accuracy, precision, recall, and confusion matrix

# Results

### Exploratory Data Analysis (EDA)
- **Age:** Majority of participants are between 40–60 years old.
- **BMI:** Most values fall between 20–30, indicating a tendency toward overweight status.
- **Categorical Analysis:** Smokers and males appear more frequently in the positive heart disease/stroke class.
- **Correlation:** Age, systolic BP, BMI, and cholesterol showed notable relationships with heart disease/stroke.

The baseline Logistic Regression model achieved an accuracy of approximately 85.19%. Although overall accuracy was high, the model struggled to correctly identify positive heart disease/stroke cases, highlighting the impact of class imbalance. Feature scaling slightly improved the model's performance.

![DistributionPlots_HistogramAge_color](https://github.com/user-attachments/assets/a600ccbb-e7c8-4e9b-a297-ae520e481ba5)

![DistributionPlots_HistogramBMI_with_without_outlier](https://github.com/user-attachments/assets/a90a5a76-4e7d-4e23-a25a-b96e32a6043a)

![BarPlot_SmokevsHeartStroke](https://github.com/user-attachments/assets/f526265b-8465-45e6-9ffa-c7f590003da0)

![BarPlot_GendervsHeartStroke](https://github.com/user-attachments/assets/a95cf6b0-d3ed-43c4-9ad5-49f3f580db4c)

![CorrelationHeatmap](https://github.com/user-attachments/assets/e59dc24c-fe4a-41a6-a6f0-7432cf3bbbad)

![Confusion_Matrix2](https://github.com/user-attachments/assets/7bd8e843-d59e-4176-b6d7-131e3b89028c)



# Next Steps

- Explore advanced models like Random Forest, XGBoost, and Gradient Boosting to improve recall.
- Apply techniques like SMOTE (Synthetic Minority Over-sampling) to balance the dataset.
- Conduct hyperparameter tuning to optimize model performance.
- Deploy the model in a simple app interface for practical health screening applications.


   # Outline of Project

  https://github.com/Sara-Oberg/heart-disease-capstone-project/blob/main/Heart_Disease_Capstone_Project_Sara_Obergassel_26April2025.ipynb

  
  https://github.com/Sara-Oberg/heart-disease-capstone-project/blob/main/docs
  
  https://github.com/Sara-Oberg/heart-disease-capstone-project/blob/main/docs/Heart_Project_Capstone_Project_Sara_Obergassel_26April2025.docx

  
  
