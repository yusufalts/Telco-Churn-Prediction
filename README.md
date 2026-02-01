# Telco-Churn-Prediction
machine learning project for customer churn prediction in the telecom domain.

Business Problem
You are asked to develop a machine learning model that can predict customers who will leave the company.
You are expected to perform the necessary data analysis and feature engineering steps before developing the model.
Dataset Story
Telco customer churn contains information about a fictitious telecom company providing home phone and Internet services to 7043 customers in California in the third quarter. It includes which customers left, stayed or signed up for service.

The data set consists of 21 Variables and 7043 Observations.

CustomerId : Customer Id

Gender : Gender
SeniorCitizen : Whether the customer is a senior citizen (1, 0)
Partner : Whether the client has a partner (Yes, No) ? Married or not. Living together, being roommates
Dependents : Whether the client has dependents (Yes, No) (Child, mother, father, grandmother)
tenure : Number of months the customer stays with the company
PhoneService : Whether the customer has phone service (Yes, No)
MultipleLines : Whether the customer has more than one line (Yes, No, No phone service)
InternetService : Customer's internet service provider (DSL, Fiber optic, No)
OnlineSecurity : Whether the customer has online security (Yes, No, No Internet service)
OnlineBackup : Whether the customer has online backup (Yes, No, No Internet service)
DeviceProtection : Whether the customer has device protection (Yes, No, No Internet service)
TechSupport : Whether the customer receives technical support (Yes, No, No Internet service)

StreamingTV : Whether the customer has streaming TV (Yes, No, no Internet service) (The customer has a third-party indicates whether the provider uses the Internet service to broadcast television programs)

StreamingMovies : Whether the customer has streaming movies (Yes, No, No Internet service) (Customer has a third-party Indicates whether the customer is using the Internet service to stream movies from the provider)

Contract : Duration of the customer's contract (Month to month, One year, Two years)

PaperlessBilling : Whether the customer has a paperless bill (Yes, No)
PaymentMethod : Customer's payment method (Electronic check, Postal check, Bank transfer (automatic), Credit card (automatic)
MonthlyCharges : Amount charged to the customer monthly
TotalCharges : Total amount charged to the customer
Churn : Whether the customer is using or not (Yes or No) - Customers who left in the last month or quarter.

Each row represents a unique customer. Variables contain information about customer service, account and demographic data.

Services that customers sign up for => phone, multiple lines, internet, online security, online backup, device protection, technical support and TV and movie streaming.
Customer account information => how long they have been a customer, contract, payment method, paperless billing, monthly fees and total fees.
Demographic information about clients => gender, age range and partners and dependents whether or not
Road Map
1. Import Required Libraries

2. Adjusting Row Column Settings

3. Loading the data Set

4. Exploratory Data Analysis

5. Capturing / Detecting Numeric and Categorical Variables

6. Analysis of Categorical Variables

7. Analysis of Numerical Variables

8. Analysis of Numeric Variables by Target

9. Analysis of Categorical Variables by Target

10. Examining the Logarithm of the Dependent Variable

11. Correlation Analysis

12. Feature Engineering

13. Missing Value Analysis

14. Outlier Analysis

15. Base Model

16. Comparison of Metrics for Different Models Before Feature Engineering

17. Feature Importance For Base Model

18. Feature Extraction

19. ENCODING

20. Standardization Process

21. Creating Model

22. Comparison of Metrics for Different Models After Feature Engineering

23. Feature Importance

24. Metric Improvement Comparison After Feature Engineering

25. Hyperparameter Optimization
