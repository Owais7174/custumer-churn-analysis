Telco Customer Churn Analysis

Overview:

This repository contains a comprehensive analysis of customer churn for a telecommunications company. The goal of this project is to understand the factors contributing to customer churn and to visualize the data to derive actionable insights.


Table of Contents:

Project Description

Dataset

Technologies Used

Analysis Steps

Visualizations

Results

Contributing

License


Project Description

Customer churn is a critical issue for telecommunications companies, as retaining existing customers is often more cost-effective than acquiring new ones. This analysis aims to identify patterns and trends in customer behavior that lead to churn, using various data visualization techniques and statistical methods.


Dataset

The dataset used for this analysis is the Telco Customer Churn dataset, which includes the following columns:

customerID: Unique identifier for each customer

gender: Gender of the customer

SeniorCitizen: Indicates if the customer is a senior citizen (1 = Yes, 0 = No)

Partner: Indicates if the customer has a partner (Yes/No)

Dependents: Indicates if the customer has dependents (Yes/No)

tenure: Number of months the customer has been with the company

PhoneService: Indicates if the customer has phone service (Yes/No)

MultipleLines: Indicates if the customer has multiple lines (Yes/No)

InternetService: Type of internet service (DSL, Fiber optic, No)

OnlineSecurity: Indicates if the customer has online security (Yes/No)

OnlineBackup: Indicates if the customer has online backup (Yes/No)

DeviceProtection: Indicates if the customer has device protection (Yes/No)

TechSupport: Indicates if the customer has tech support (Yes/No)

StreamingTV: Indicates if the customer has streaming TV (Yes/No)

StreamingMovies: Indicates if the customer has streaming movies (Yes/No)

Contract: Type of contract (Month-to-month, One year, Two year)

PaperlessBilling: Indicates if the customer has paperless billing (Yes/No)

PaymentMethod: Method of payment (Electronic check, Mailed check, etc.)

MonthlyCharges: Monthly charges for the customer

TotalCharges: Total charges incurred by the customer

Churn: Indicates if the customer has churned (Yes/No)


Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook


Analysis Steps

Data Cleaning:

Handle missing values and incorrect data types.
Convert categorical variables for better analysis.


Exploratory Data Analysis (EDA):

Analyze the distribution of churned vs. non-churned customers.
Investigate the impact of various features on customer churn.


Visualization:

Create visualizations to represent the findings from the EDA.
Use bar charts, pie charts, and histograms to illustrate key insights.


Insights and Conclusions:

Summarize the findings and provide recommendations based on the analysis.


Visualizations:

Count of Customers by Churn

Percentage of Churned Customers

Churn by Gender

Churn by Senior Citizen Status

Churn by Contract Type

Churn by Payment Method


Results:

Approximately 26.54% of customers have churned.

Senior citizens have a higher churn rate compared to younger customers.
Customers with month-to-month contracts are more likely to churn.
The use of services like Online Security and Tech Support correlates with lower churn rates
