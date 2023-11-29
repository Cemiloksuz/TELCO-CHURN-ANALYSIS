# TELCO-CHURN-ANALYSIS
This project includes feature engineering operations, which is the first step in developing a machine learning model.
A made-up telecom company in California that offers home phone and Internet wants to create a machine learning model that can tell which users are likely to leave. The project's goal is to use different machine learning models to make a system that can predict which customers will not come back. This was done with the Random Forest, XGBoost, LightGBM, and CatBoost algorithms.



Content Telco customer churn data has details about a made-up telecom company that served 7043 people in California with home phone and Internet service in the third quarter. That tells them which people left, stayed, or signed up for their service.



Rows of columns
CustomersId: The customer ID
Type: Gender Type
Checks to see if the customer is an older person (1, 0).
Partner: If the person has a partner (Yes, No).
Dependents: If the client has dependents (Yes, No); Length of Stay: How long the customer stays with the company;
Checks to see if the customer has phone service (Yes, No).
Checks to see if the customer has more than one line (Yes, No, No phone service).
Internet Service: The supplier of the customer's internet (DSL, Fiber optic, No)
Checks to see if the customer has internet security (Yes, No, No Internet service).
Checks to see if the customer has an internet backup (Yes, No, No Internet service).
If the customer has device security (Yes, No, No Internet service), this field will be empty.
TechSupport: If the customer gets technical help (Yes, No, No Internet service)
Check to see if the customer has live TV (Yes, No, No Internet service).
Checks to see if the customer has streaming movies (Yes, No, No Internet service).
deal: The length of the customer's deal (month to month, one year, two years)
No paperBilling: Does the customer have an electronic bill (Yes, No)?
Payment Method: The way the customer wants to pay (electronic check, postal check, automatic bank transfer, or credit card)
MonthlyCharges: The amount the customer is charged every month
TotalCharges: The full amount that the customer was charged
Turn around If the customer used it or not (Yes or No)


Flow


After the data was uploaded, it was mostly examined, and some changes were made to the structure.
Captured are categorical and numerical fields.
An study of outliers was done. By suppressing them, outliers were changed to upper and lower limits.
There was a missing value study, and the issues were fixed.
Through feature engineering, many new sections have been added.
Label endocing was used on values that were binary.
One-hot encoding was used on categorical values with more than one class.
Standardization was used on factors that were numbers.
Over the train data, dependent and independent factors were made.
Different methods were used to choose which models to build.
For the models, the Random Forest, XGBoost, LightGBM, and CatBoost algorithms were used.
We talked about how important features are.
