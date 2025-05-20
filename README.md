# Exploratory Data Analysis on Student Depression Dataset
This repository contains the complete mini-project work on **Exploratory Data Analysis (EDA)** conducted on a dataset focused on **student mental health and depression**. The project was completed as part of the Term Work for the BCA (Artificial Intelligence and Machine Learning) program at **Ajeenkya DY Patil University, Pune**.

#Project Summary
The project investigates various factors contributing to depression among students using a real-world dataset. With increasing concerns around student mental health, this EDA project aims to uncover patterns and correlations using statistical and visual analysis.

# Objectives
- Understand the relationships between lifestyle, academic stress, and depression.
- Clean and preprocess the dataset for meaningful analysis.
- Use visualizations to reveal trends and distributions.
- Build a logistic regression model for preliminary classification of depression status.
- Derive insights to inform mental health interventions.

# Dataset Overview
The dataset contains **1000 records** with the following attributes:
- `Gender`, `Age`, `Academic Pressure`, `Work Pressure`
- `CGPA`, `Study Satisfaction`, `Job Satisfaction`
- `Sleep Duration`, `Dietary Habits`
- `Suicidal Thoughts`, `Financial Stress`
- `Family History of Mental Illness`, `Depression` (Target Variable)

# Tools & Libraries
Python
Pandas, NumPy – Data manipulation
Matplotlib, Seaborn – Data visualization
Scikit-learn – Machine learning and model evaluation
Google Colab – Development environment

# Key Visualizations
Line Plot: Age vs CGPA
Bar Chart: Depression Count by Gender
Pie Chart: Sleep Duration Distribution
Histogram: Financial Stress Levels
KDE Plot: CGPA Distribution


#Model Development
A "Logistic Regression" model was trained to classify depression based on lifestyle and academic features.
Steps:
1. One-hot encode categorical variables
2. Train-test split the data
3. Fit logistic regression
4. Evaluate using:
   - Accuracy
   - Confusion Matrix
   - Classification Report

# Results & Insights
Students with lower CGPA, poor sleep, and higher financial stress showed higher chances of depression.
Female students** had a slightly higher rate of reported depression.
Suicidal thoughts** strongly correlated with depression status.
Students sleeping less than 6 hours were more vulnerable.



