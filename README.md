# DevelopersHubCo_Intern_Laiba-Wazir
# Data Science &amp; Analytics Internship.
---

## Task 01: Exploring and Visualizing a Simple Dataset

*Task Objective:*

The objective of this task was to explore, summarize, and visualize a simple dataset (Iris Dataset) to understand its structure, relationships between variables, and data distribution.

*My Approach:*

I loaded the Iris dataset using pandas and examined its structure with .shape, .columns, and .head(). I then created various visualizations using matplotlib and seaborn, including:

Scatter plots to study relationships between features

Histograms to observe the distribution of each variable

Box plots to detect outliers and understand the spread of values

*Results and Insights:*

The scatter plots revealed clear separation between species for some feature combinations. Histograms showed distinct distributions for petal and sepal measurements. Box plots highlighted that certain features, like petal length, vary significantly between species, which can be useful for classification tasks.

---

## Task 02: Credit Risk Prediction 

*Task Objective:*

The goal of this task was to predict whether a loan applicant is likely to default on a loan using the Loan Prediction dataset from Kaggle.

*My Approach:*

I started with data cleaning by handling missing values for both numerical and categorical columns. Then, I performed Exploratory Data Analysis (EDA) to visualize key features such as loan amount, education level, and income using bar plots, histograms, and boxplots.
For modeling, I trained classification algorithm including Logistic Regression, and evaluated them using accuracy score and confusion matrix to measure predictive performance.

*Results and Insights:*

The analysis showed that features like Applicant Income, Loan Amount, and Education had a strong influence on loan default prediction. The confusion matrix helped identify where the models misclassified defaults vs. non-defaults, highlighting potential improvement areas through better feature engineering.

---

## Task 03: Customer Churn Prediction (Bank Customers)

*Task Objective:*

The goal of this task was to predict whether a bank customer is likely to churn (leave the bank) using the Churn Modelling dataset.

*My Approach:*

I began by cleaning and preparing the dataset, handling missing values, and encoding categorical features such as Geography and Gender using One-Hot Encoding. I then trained a Logistic Regression model to classify churn and analyzed feature importance by inspecting the model’s coefficients to see which variables most influenced customer churn.

*Results and Insights:*

The model achieved good classification accuracy, with features such as Geography, Credit Score, and Age showing the highest influence on churn probability. Feature importance visualization helped identify which customer characteristics contribute most to churn, which can guide targeted customer retention strategies.

---


