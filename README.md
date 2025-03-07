# Customer-Churn-Prediction
Project Overview:
The main objective of the Customer Churn Prediction project is to analyze the demographics and financial information of bank customers, including factors like age, gender, contract, payment method, paperless billing, monthly charges, and more, in order to predict whether a customer will buy the service or not. Customer churn, the decision of customers to buy a sevice from the company or not , can significantly impact the Telcocompany's business and profitability. By accurately predicting customer churn, the company can take proactive measures to retain valuable customers and enhance customer satisfaction.

## About the Dataset:
The dataset used in this project is sourced from Kaggle and comprises 7043 rows (customers) and 21 columns (features). The dataset's primary objective is to predict whether a customer will churn (buy a service) based on their gender, age range, and if they have partners and dependents.

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The data set includes information about:

Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

## Steps for Processing and Building the Project
### 1. Understand the Dataset
Column Name :	Description

customerID  : Unique identifier for each customer.

gender      : Male or Female.

SeniorCitizen: Whether the customer is a senior citizen (1) or not (0).

Partner/Dependents: Whether the customer has a partner or dependents (Yes/No).

tenure: Number of months the customer has stayed with the company.

PhoneService/MultipleLines: Whether the customer has phone service or multiple lines.

InternetService: Type of internet service (DSL, Fiber optic, No).

OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV

StreamingMovies: Additional services the customer has subscribed to (Yes/No).

Contract: Type of contract (Month-to-month, One year, Two year).

PaperlessBilling: Whether the customer is using paperless billing (Yes/No).

PaymentMethod: Method of payment (Electronic check, Mailed check, Bank transfer, Credit card).

MonthlyCharges: The amount charged to the customer monthly.

TotalCharges: Total amount charged to the customer.

Churn: Target variable — whether the customer has churned (Yes/No).

### 2. Data Preprocessing
  #### a)Handle Missing Values: (TotalCharges sometimes has blanks).
  #### b)Encode Categorical Variables: (e.g., gender, InternetService, Contract)
  #### c)Scale Numerical Features: (Normalize numerical columns like tenure, MonthlyCharges, and TotalCharges)
  #### d)Convert Target Variable: (Encode Churn column as 0 for "No" and 1 for "Yes".)
  
### 3. Exploratory Data Analysis (EDA):
  #### Visualization
  ->Bar chart for churn rate by Contract.
  ![21 01 2025_00 57 47_REC](https://github.com/user-attachments/assets/dc6b3b0e-c0d3-482a-a8f0-fe8cac9908a5)


  ->Box plot for MonthlyCharges by Churn.
![21 01 2025_00 57 20_REC](https://github.com/user-attachments/assets/35b031aa-e724-4849-8422-1d6e4a569add)
  

  -> Pie chart for InternetService distribution.
  
  ![pie chrt](https://github.com/user-attachments/assets/ded5d7e7-b6ac-4bf5-9ec8-0bad20047e92)
  ![block chart](https://github.com/user-attachments/assets/bb61207d-30e6-4b8a-9466-fd946e8e126c)
  ![21 01 2025_00 57 34_REC](https://github.com/user-attachments/assets/4e5ae45d-4500-4639-b478-3ada0667ed3a)
  


### 4. Build the Machine Learning Model
### 5. Interpret and Document Results
  
  
        
By leveraging this dataset and employing appropriate data science techniques, the project aims to build a predictive model that can accurately identify customers likely to churn, enabling the bank to implement targeted retention strategies and ultimately improve customer loyalty and business performance.
