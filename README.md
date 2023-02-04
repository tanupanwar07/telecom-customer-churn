TELECOM CUSTOMER CHURN PREDICTION USING MACHINE LEARNING  

Predicting customer churn is critical for telecommunication companies to be able to effectively retain customers. It is more costly to acquire new customers than to retain existing ones. For this reason, large telecommunications corporations are seeking to develop models to predict which customers are more likely to change and take actions accordingly.

CONTENT:
the data set contains 19 independent variables, which can be classified into 3 groups:

(1) Demographic Information

gender: Whether the client is a female or a male (Female, Male).
SeniorCitizen: Whether the client is a senior citizen or not ( 0, 1).
Partner: Whether the client has a partner or not (Yes, No).
Dependents: Whether the client has dependents or not (Yes, No).
(2) Customer Account Information

tenure: Number of months the customer has stayed with the company (Multiple different numeric values).
Contract: Indicates the customer’s current contract type (Month-to-Month, One year, Two year).
PaperlessBilling: Whether the client has paperless billing or not (Yes, No).
PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit Card (automatic)).
MontlyCharges: The amount charged to the customer monthly (Multiple different numeric values).
TotalCharges: The total amount charged to the customer (Multiple different numeric values).
(3) Services Information

PhoneService: Whether the client has a phone service or not (Yes, No).
MultipleLines: Whether the client has multiple lines or not (No phone service, No, Yes).
InternetServices: Whether the client is subscribed to Internet service with the company (DSL, Fiber optic, No)
OnlineSecurity: Whether the client has online security or not (No internet service, No, Yes).
OnlineBackup: Whether the client has online backup or not (No internet service, No, Yes).
DeviceProtection: Whether the client has device protection or not (No internet service, No, Yes).
TechSupport: Whether the client has tech support or not (No internet service, No, Yes).
StreamingTV: Whether the client has streaming TV or not (No internet service, No, Yes).
StreamingMovies: Whether the client has streaming movies or not (No internet service, No, Yes).

Front end looks like:

![Telco6](https://user-images.githubusercontent.com/109168677/216071455-ba29af92-3522-4f02-bb5b-7431669f4ad4.jpeg)

     
     
    In this repository, we have performed the end to end Exploratory Data Analysis,
    and idenfitied the characteristics of the customers that are more likely to churn, 
    and  to create a ML model .
        
 
 
🟢 For EDA, please refer to : Churn Analysis - EDA.ipynb

🟢 For Model Building, please refer to: Churn Analysis - Model Building.ipynb

🟢 For Model Deployment, please refer to app.py
