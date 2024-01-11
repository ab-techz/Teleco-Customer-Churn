# Churn Analysis

  ![8688fe001a6514d8b406e08f46c1a271](https://github.com/ab-techz/Teleco-Customer-Churn/assets/142206534/660bff7c-c3db-4d13-9078-116ac228c870)

## Introduction
This project focuses on the Exploratory Data Analysis (EDA) of the Telecom Churn dataset. The objective is to provide actionable insights to the business on reducing churn based on the observations derived from the analysis. Following the EDA,a Decision Tree Classifier has been integrated to predict whether a customer is likely to churn, categorizing the outcome as "Yes" or "No."(checkout the .ipynb file for that)



## About the dataset.
The dataset contains information on customers of a telecom company, including their demographic information such as gender and age, as well as their account information such as the services they subscribe to, their tenure with the company, and their billing information. The target variable in the dataset is "Churn," which indicates whether a customer has terminated their service with the company.

- *CustomerID:* Unique identifier for each customer.
 *gender:* The gender of the customer (e.g., Male, Female).
- *Partner:* Indicates whether the customer has a partner (Yes/No).
- *Dependents:* Indicates whether the customer has dependents (Yes/No).
- *tenure:* The duration of the customer's association with the service in months.
- *PhoneService:* Indicates whether the customer has a phone service (Yes/No).
- *MultipleLines:* Indicates whether the customer has multiple lines for phone service (Yes/No).
- *InternetService:* Type of internet service subscribed by the customer.
- *OnlineSecurity:* Indicates whether the customer has online security services (Yes/No).
- *OnlineBackup:* Indicates whether the customer has online backup services (Yes/No).
- *DeviceProtection:* Indicates whether the customer has device protection services (Yes/No).
- *TechSupport:* Indicates whether the customer has tech support services (Yes/No).
- *StreamingTV:* Indicates whether the customer has streaming TV services (Yes/No).
- *StreamingMovies:* Indicates whether the customer has streaming movie services (Yes/No).
- *Contract:* The type of contract the customer has (e.g., Month-to-month, One year, Two years).
- *PaperlessBilling:* Indicates whether the customer receives paperless billing (Yes/No).
- *PaymentMethod:* The method used by the customer for payment.
- *MonthlyCharges:* The amount charged to the customer per month.
- *TotalCharges:* The total charges incurred by the customer.
- *Churn:* Indicates whether the customer has churned (Yes/No).
- 
These descriptions provide an overview of the information each column contains.

## Insights
![images](https://github.com/ab-techz/Teleco-Customer-Churn/assets/142206534/573b7c30-31d6-4d68-82f1-3be34a8e06f8)

- Gender distribution of the customers is almost equal,(count of male customers is slightly higher than the female customers)
- It is evident that maximum customers fall in the month-to-month criteria mainly because it is more affordable. Followed by two-year contracts and lastly one year contracts.
- Interestingly, the majority of monthly contracts only last a few weeks to a few months, although two-year contracts often continue for over 70 months. This demonstrates that clients who sign longer contracts are more loyal to the company and have a greater tendency to stick with it.
- 74% of the clients in our database do not churn while 26.5% of the clients churn. Since a sizable portion of the clients should remain loyal, the data is obviously skewed. We must keep this in mind for our modelling because skewness may result in several false negatives.

## Suggestions
- Maximum users who churned fall in month-to-month contracts, to increase user retention the company can bring out some new short term offers to keep the users engaged and not leave.
- Senior citizens account for only 16.2%, their churn rate is still high, a special plan for senior citizen can definitely be brought up. This would also help with goodwill of the company.
- Coming up with new strategies and lucrative offers can help the business to prosper.

