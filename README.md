 Telecom Customer Retention  

## Project Overview  
The aim of this data science project is to analyze customer demographics, services, tenure, and other variables to predict whether a particular customer will churn or not. Churn, in this context, refers to customers leaving the telecommunications company's services. By understanding the factors that contribute to churn, the company can take proactive measures to retain customers.  

## Data Dictionary  
Here is a data dictionary describing the variables used in this project:  

| Variable          | Description                                                                                     |  
|-------------------|-------------------------------------------------------------------------------------------------|  
| CustomerID        | Unique customer ID                                                                             |  
| Gender            | Customer's gender                                                                               |  
| SeniorCitizen     | Whether the customer is a senior citizen or not (1, 0)                                        |  
| Partner           | Whether the customer has a partner or not (Yes, No)                                           |  
| Dependents        | Whether the customer has dependents or not (Yes, No)                                          |  
| Tenure            | Number of months the customer has stayed with the company                                      |  
| PhoneService      | Whether the customer has a phone service or not (Yes, No)                                      |  
| MultipleLines     | Whether the customer has multiple lines or not (Yes, No, No phone service)                    |  
| InternetService   | Customer’s internet service provider (DSL, Fiber optic, No)                                   |  
| OnlineSecurity    | Whether the customer has online security or not (Yes, No, No internet service)                |  
| OnlineBackup      | Whether the customer has online backup or not (Yes, No, No internet service)                  |  
| DeviceProtection  | Whether the customer has device protection or not (Yes, No, No internet service)              |  
| TechSupport       | Whether the customer has tech support or not (Yes, No, No internet service)                   |  
| StreamingTV       | Whether the customer has streaming TV or not (Yes, No, No internet service)                   |  
| StreamingMovies    | Whether the customer has streaming movies or not (Yes, No, No internet service)              |  
| Contract          | The contract term of the customer (Month-to-month, One year, Two years)                      |  
| PaperlessBilling  | Whether the customer has paperless billing or not (Yes, No)                                   |  
| PaymentMethod     | The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)) |  
| MonthlyCharges    | The amount charged to the customer monthly                                                      |  
| TotalCharges      | The total amount charged to the customer                                                        |  
| Churn             | Whether the customer churned or not (Yes or No)                                               |  

## Conclusions  
From the exploratory data analysis, the following insights have been derived:  

1. Senior citizens exhibit a lower churn rate compared to younger customers.  
2. Customers who are single or do not have dependents tend to have a higher churn rate.  
3. Customers generally express higher satisfaction with streaming services compared to services like online backup and device protection, leading to lower churn rates for streaming services.  
4. Tenure has an inverse relationship with churn rate, with customers having a tenure shorter than 5 months exhibiting a higher churn rate.  
5. Customers with month-to-month contracts are more likely to churn compared to those with one- or two-year contracts, indicating that longer contract durations are associated with lower churn rates.  
6. Customers with higher monthly charges and lower total charges are more likely to churn, suggesting the company should consider reducing monthly charges to mitigate churn.  
7. The most important features for predicting customer churn, as determined by feature importance analysis, include tenure, contract type, monthly charges, and total charges.  
