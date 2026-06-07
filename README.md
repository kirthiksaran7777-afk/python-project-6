Customer Churn Analysis System

Project Overview

Customer churn is one of the most critical challenges faced by modern businesses, especially in sectors such as banking, telecommunications, e-commerce, and subscription-based services. Churn refers to the situation where customers stop using a company’s product or service. High churn rates directly impact revenue, profitability, and long-term business sustainability.

Organizations collect vast amounts of customer data, including demographic details, financial information, usage behavior, and engagement levels. However, analyzing this data manually is inefficient and time-consuming. Moreover, due to privacy concerns and data protection regulations, real-world datasets are often not accessible for students and researchers.

To overcome these challenges, this project introduces a Customer Churn Analysis System using Synthetic Data. The dataset is generated using the Python Faker library, which simulates realistic customer information without compromising privacy. The project then applies Exploratory Data Analysis (EDA) techniques to uncover patterns, trends, and relationships that influence customer churn.

Objectives

The primary goal of this project is to analyze customer churn behavior using a synthetic dataset and derive meaningful insights. The specific objectives include:

Generate a large-scale, realistic synthetic dataset
Simulate real-world customer behavior scenarios
Perform data cleaning and preprocessing
Apply statistical analysis techniques
Identify patterns and trends influencing churn
Perform group-based and relationship analysis
Visualize data using various charts and graphs
Provide actionable insights for reducing churn
Dataset Description

The dataset consists of 100,000 synthetic customer records generated using Faker. Each record represents a customer with multiple attributes that influence churn behavior.

Column Name	Description
Customer_ID	Unique identifier for each customer
Age	Customer age (18–70 years)
Gender	Male / Female
Tenure	Number of years with the company (0–10)
Balance	Account balance (0–200,000)
CreditScore	Credit score (300–900)
EstimatedSalary	Annual income (10,000–150,000)
NumOfProducts	Number of products used (1–4)
IsActiveMember	Activity status (0 = No, 1 = Yes)
Churn	Target variable (0 = No, 1 = Yes)
Technologies Used

Python
Pandas
NumPy
Matplotlib
Heatmap
Faker
Project Workflow

1. Data Generation

Synthetic data is generated using the Faker library
Randomized logic is applied to simulate real-world conditions
Dataset includes realistic distributions for age, balance, salary, etc.
2. Data Cleaning & Preprocessing

Checked for missing or null values
Verified data types and corrected inconsistencies
Ensured dataset is clean and ready for analysis
3. Exploratory Data Analysis (EDA)

Calculated statistical measures such as mean, median, and standard deviation
Analyzed distribution of features
Identified outliers and anomalies
4. Churn Behavior Analysis

Compared churned and non-churned customers
Identified high-risk churn segments
Evaluated impact of multiple features on churn
5. Group-Based Analysis

Age groups vs churn
Gender vs churn
Active vs inactive customers
Product usage vs churn
6. Relationship Analysis

Balance vs churn
Credit score vs churn
Tenure vs churn
7. Data Visualization

Bar charts
Pie charts
Histograms
Box plots
Scatter plots
Heatmap
Key Insights

Customers with low account balance are more likely to churn
Customers with low credit scores show higher churn rates
Inactive customers are at the highest risk of churn
Customers using multiple products tend to stay longer
Higher engagement and activity significantly reduce churn probability
Customers with longer tenure are generally more loyal
<img width="833" height="592" alt="Screenshot (87)" src="https://github.com/user-attachments/assets/9237db85-9650-43e6-9737-342da43996e1" />
<img width="510" height="526" alt="Screenshot (88)" src="https://github.com/user-attachments/assets/93c5e15b-53bb-4259-be1b-3544ae7c1808" />
<img width="795" height="548" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/453f65b7-0559-455a-b7ef-c475f9968f77" />
<img width="824" height="580" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/22457e24-46dd-4b1e-80e5-0a99aa7ef916" />
<img width="781" height="578" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/22f7ecd4-0cfd-4cec-a15a-e81119ccf056" />
<img width="990" height="749" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/fbb336f6-607f-4d2d-aeb6-90f288d628c8" />




