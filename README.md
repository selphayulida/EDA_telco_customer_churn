# Understanding Customer Churn Behavior in Telecom Industry by Exploratory Data Analysis (EDA)

## Overview
In the digital era that is growing rapidly today, everyone certainly cannot escape the need for telecommunications (smartphones). Telecommunication service providers are also competing to provide various types of telecommunication services with various conveniences and benefits for customers. In every business,  company always wants to keep its customers always using its services, as well as in the telecommunications industry. Understanding customer behavior through data will certainly help a company take business efforts in retaining its customers. Therefore, it is important for a company to analyze customer churn as a basis for making business strategies to retain customers.

Customer churn is a business metric that measures the number of customers who have stopped using the company's products or services. Every company certainly wants to reduce or prevent customer churn and increase customer lifetime value (CLV). In this mini-project, I used a dataset from Kaggle which provided customer information data from a Telcom company and did a deep-dive analysis in the EDA process to get a better understanding of the data.


## The Data
The data in this project is sourced from Kaggle https://www.kaggle.com/datasets/blastchar/telco-customer-churn
This dataset consists of 7043 rows and 21 columns. The following is a description of the dataset that will be analyzed to help understand what data we will use in this project.
1. `customerID`: Customer ID.
2. `gender`: Customer gender (Male/ Female).
3. `SeniorCitizen`: Whether the customer is a senior citizen (65 or older) or not. (1= Senior Citizen; 0=non Senior Citizen).
4. `Partner`: Indicates if customer has partner or not/single (Yes/ No).
5. `Dependents`: Whether the customer has dependents or not (Yes/No). Dependents can be children, parents, etc.
6. `tenure`: Represents the total number of months that customers have been with the company.
7. `PhoneService`: Indicates whether the customer subscribes to the phone service or not (Yes/ No).
8. `MultipleLines`: Indicates whether the customer subscribes to multiple lines (Yes/ No).
9. `InternetService`: Indicates the customer's internet service type (DSL/ Fiber Optic/ No).
10. `OnlineSecurity`: Indicates whether the customer subscribes to additional online security services (Yes/ No/ No internet service).
11. `OnlineBackup`: Indicates whether the customer subscribes to an additional online backup service (Yes/ No/ No internet Service).
12. `DeviceProtection`: Indicates whether the customer subscribes to additional Device Protection for their Internet equipment (Yes/ No/ No internet service).
13. `TechSupport`: Indicates whether the customer is subscribed to an additional Technical Support package (Yes/No/ No internet service).
14. `StreamingTV`: Indicates whether subscribers use their Internet service to stream television programs (Yes/ No/ No internet service).
15. `StreamingMovies`: Indicates whether subscribers use their Internet service to stream television programs (Yes/ No/ No internet service).
16. `Contract`: Shows the customer's current contract type (Month-to-month/ One year/ Two year).
17. `PaperlessBilling`: Indicates whether the customer uses paperless billing (Yes/ No).
18. `PaymentMethod`: Shows the customer's choice of how to pay for their bill (Electronic check/ Mailed check/ Bank transfer (automatic)/ Credit card (automatic)).
19. `MonthlyCharges`: Shows the customer's current total monthly charges for all the services they use.
20. `TotalCharges`: Shows the total cost of the customer
21. `Churn`: Shows Customer churn status (Yes/ No).

## EDA Steps
The following are the EDA steps carried out in this project.
1. Data Cleansing
   - Column understanding
   - Clean the data (Drop whitespace rows, check/work on missing values, check/work on duplicated values)
2. Standard EDA
   - Statistical summary of each column
   - Univariate analysis
   - Multivariate analysis
3. Set deep-dive questions
   - Check the standard EDA results, whether there are interesting findings in the form of business insights that need to be further analyzed with data. Then write down these questions for further deep-dive analysis.
4. Answer the questions and conclusion
   - Further preprocess/manipulate the data for answering the questions to get business insight related to customer churn.
