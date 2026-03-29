Introduction

Customer churn is a critical metric for businesses, especially in industries such as banking, telecommunications, and subscription-based services. It refers to the phenomenon where customers stop using a company’s products or services over a given period. Understanding and predicting churn is essential, as acquiring new customers is often more expensive than retaining existing ones.

This project focuses on generating a large-scale synthetic dataset that mimics real-world customer behavior. By simulating various attributes such as demographic details, financial status, and engagement levels, the dataset provides a practical foundation for analyzing patterns that influence customer retention. A simple rule-based approach is used to label churn, enabling users to explore relationships between features and churn outcomes.

The primary goal of this project is to support learning and experimentation in data analysis, visualization, and machine learning. It allows users to practice exploratory data analysis (EDA), build predictive models, and gain insights into factors that contribute to customer churn in a controlled and reproducible environment.

 Features
Generates 100,000 synthetic customer records
Includes demographic and financial attributes
Implements rule-based churn classification
Performs statistical analysis
Provides multiple data visualizations
Exports dataset as a CSV file
Churn Logic

Customers are labeled as churned (Churn = 1) when they meet all of the following conditions:

Low account balance (< 50,000)
Inactive membership status
Low credit score (< 500)

Otherwise, customers are considered retained (Churn = 0).
 Dataset Structure
Column Name	Description
Customer_ID	Unique identifier
Age	Customer age (18–70)
Gender	Male/Female
Tenure	Years with company (0–10)
Balance	Account balance
CreditScore	Credit score (300–900)
EstimatedSalary	Annual salary
NumOfProducts	Number of products used
IsActiveMember	1 = Active, 0 = Inactive
Churn	1 = Churned, 0 = Retained
 Exploratory Data Analysis (EDA)

The project includes basic data analysis and visualization to understand patterns in the dataset:

Checking missing values
Summary statistics (mean, median, standard deviation)
Churn distribution analysis
Visual exploration using plots and charts
 Visualizations
Count plots for churn distribution
Gender vs churn comparison
Age distribution histogram
Balance vs churn boxplot
Credit score vs balance scatter plot
Correlation heatmap
Churn percentage pie chart
