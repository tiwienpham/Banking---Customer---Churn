![Churn](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/ed6e0bb4-2310-4cb7-9f18-0ff457472d06)


# Banking-Customer-Churn-Prediction.
## Introdution
Welcome to the repository for the **Banking Customer Churn Prediction** project! In this project, I aim to develop a model that can accurately predict customer churn in the banking industry. Customer churn refers to the phenomenon where customers discontinue their relationship with a business, and it is a critical challenge for banks as it directly impacts their profitability and growth.

The objective of this project is to leverage machine learning techniques and historical customer data to build a predictive model that can identify customers who are likely to churn. By identifying these customers in advance, banks can proactively take measures to retain them, such as offering personalized incentives or improving customer service.

## Objectives.
- Calculate the percentage of bank churned customers in the dataset and identify the proportion of customers who continue using the bank's services.
- Analyze the dataset to identify key features that are responsible for bank customer churn. Explore various attributes such as demographics, credit score, has CrCard, Gender, Age,... to understand their influence on churn behavior.
- Evaluate and select the most suitable machine learning model for accurately classifying churn and non-churn customers. Consider models such as Logistic Regression, Decision Trees, Random Forests, KNN, Support Vector Machine, XGB, KNeighborsClassifier and compare their performance to find the best model.

## Repository Structure.
This repository is organized as follows:
- Churn_Modelling: This directory contains the dataset used for training and evaluation.
- Banking Customer Churn Prediction: This directory contains Jupyter notebooks that walk through the various stages of the project, including data exploration, preprocessing, model development, and evaluation.
- README.md: This file provides an overview of the project, its objectives, and instructions on how to use the repository.

## Content.
**1. Import Libraries.**
![image](https://github.com/tiwienpham/alicepham.github.io/assets/119265751/e42ca076-f536-43a4-9af5-fb87afdf320a)

**2. About Dataset.**

The Bank Customer Churn Prediction dataset is a collection of data that aims to predict customer churn in the banking industry. The dataset can be accessed from the following Kaggle URL: https://www.kaggle.com/datasets/shubhammeshram579/bank-customer-churn-prediction.
The dataset contains various features related to bank customers and their interactions with the bank. It includes both numerical and categorical variables that provide valuable insights into customer behavior and potential churn patterns. The dataset includes attributes such as:
- Customer ID: A unique identifier for each customer
- Surname: The customer's surname or last name
- Credit Score: A numerical value representing the customer's credit score
- Geography: The country where the customer resides (France, Spain or Germany)
- Gender: The customer's gender (Male or Female)
- Age: The customer's age.
- Tenure: The number of years the customer has been with the bank
- Balance: The customer's account balance
- NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
- HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
- IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
- EstimatedSalary: The estimated salary of the customer
- Exited: Whether the customer has churned (1 = yes, 0 = no)
  
**3. Data Exploration.**

**a. Heatmap of Feature Correlation.**

  ![image](https://github.com/tiwienpham/alicepham.github.io/assets/119265751/4c9303f3-6ba7-4ebd-95ac-b92bb8f808eb)
  
**b. Distribution of Credit Scores.**

![Distribution of Credit Scores](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/77143ee2-d251-42c9-a487-080cfe6fdffd)
  
Based on distribution of credit score chart, I have observed a distribution within the range of 850-855. This range represents excellent credit scores and is typically associated with individuals who have a proven track record of responsible credit management, low credit utilization, and a history of timely payments.

**c. Distribution of Balance.**

![Distribution of Balance](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/4d2f07e8-8bcb-41cf-b2a3-fd5ea324cd01)

  
**d. Distribution of EstimatedSalary.**

![Distribution of EstimatedSalary](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/87344510-2cb4-4a6e-9074-87fabd5f103b)
  
**e. Tenure vs Exited.**

![Tenure vs Exited](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/f5a4d378-f8b9-4446-9715-fd9209740d28)
  
**d. Distribution of Churned Customers.**

![Distribution of Churned Customers](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/a96c231f-4e8d-4460-9939-e6cb9e4e9f18)
  
**e. Customer Distribution by Gender.**

![Customer Distribution by Gender](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/c5f96d4f-d4dd-45ef-8783-57165c36e392)

  
**f. Customer Active Membership.**

![Customer Active Membership](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/110bfb60-1580-46c0-93ff-2e36fe174c1d)
  
  **g. Customer Having Credit Card.**
  
![Customer Having Credit Card](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/24653543-8d5b-449a-b07f-8e45f1a6a04a)
  
  **h. Customers Exited with Number of products used.**
  
![Customers Exited with Number of products used](https://github.com/tiwienpham/Banking-Customer-Churn/assets/119265751/9e2500fc-9a49-4572-bb9d-a786ad8e3e62)
  
**4. Data Preprocessing.**

**5. Feature Engineering.**

Encoding Categorical Data: Categorical data, such as gender or customer membership status, needs to be transformed into numerical values before it can be used effectively in machine learning models. One common approach for encoding categorical data is one-hot encoding or creating dummy variables. By encoding categorical data, i enable machine learning models to interpret and utilize these features for analysis and prediction.
StandardScaler: Feature scaling is an essential step in data preprocessing, particularly for numerical features, to ensure all features are on a similar scale. The StandardScaler is a popular technique used to standardize numerical features.

**6. Model Development.**

In the model development phase, we select and train machine learning models to make predictions or perform classification tasks based on the available data, include:
- KNeighborsClassifier
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine
- XGBoost
- K-Nearest Neighbors

**7. Model Evaluation.**
  
To evaluate the performance and effectiveness of my trained machine learning models. I use Accuracy, Recall, Precision, F1 metrics.

**8. Deployment.**

After evaluating the models using appropriate metrics, i compare performance and select Random Forest Classifier is the best model to deploy.

## Conclusion.

By accurately predicting customer churn in the banking industry, this project provides valuable insights to banks and enables them to take proactive measures to retain their customers. I hope this repository serves as a useful resource for understanding the customer churn prediction process and inspires further research and development in this field.
