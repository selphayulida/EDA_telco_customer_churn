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

## Conclusion
After performing EDA standard and also deep dive analysis, here are some conclusions that can be got.

1. The total customer who churn is 1869 ppl or around 26.58% with Monthly charge in total is 139,130.85 (currency unit). This shows that there is a potential loss of 139,130.85 (currency unit) per month or about 30.53% ytd. 
2. The churn customers tend to have month to month contracts with an average tenure of about 14 months and a median value of 7 months. We can conclude that the customer took a contract per month for about 1 year until they churn.
3. Customers who churn with the Electronic Check payment method is very high 84,288.75 (currency unit), which is equivalent to customers who do not churn with similar/other payment methods.
4. Using paperless billing is indeed good, although data shows that churn customers use paperless billing a lot. Seems there's anything wrong with using paperless billing.  Paperless billing with the Electronic check payment method is indeed customers favorite. The use of both tends to be very simple and practical. 
5. From 7032 customers in this research object and 1869 customers who churn, 1123 churn customers are a combination of the three profiles, namely non-senior citizen, not partnered and not dependent. This figure is about 15.97% of the total customers, and 60.09% of the total churn customers.
6. Customers who enjoy TV and movie streaming  services are dominated by the younger, free and freedom generation as in above profile (non-senior citizen, no partner, no dependents). Likewise, those who do not actually use those multimedia services. 
7. Churn customers tend to have higher monthly charges, both in each of the 4 add-on services and in their combined use (online security, online backup, device protection and tech support). The difference between the addition of add-on services to churn and non-churn customers have a monthly charge difference of 3-10 (currency unit) both in the mean and median, for each add-on or in combination. But why even if they have additional services, why do customers who churn have higher monthly charges than those who don't churn? There may be differences in rates/packages/promotions used for the add-on services.
8. Customers who use fiber optics tend to churn when compared to DSL. However, the ratio of customers who churn and not on fiber optic is greater. The total monthly charge for fiber optic customers who churn is 114,300.05 (currency units), or about 25% of the total monthly charge. This figure is quite uncomfortable because there is a loss of 25% per month (ytd). This deserves to be highlighted by the telecom company regarding whether there are (or frequently) technical problems on the fiber optic network?

In conclusion, it turns out that it is very important for telecom companies to create new strategies/campaign programs to increase Customer Lifetime Value (CLV). With the churn rate that tends to be high, especially when viewed from the total monthly charge, there is a fairly large potential loss. Some technical matters such as internet network equipment and the quality of add-on services and multimedia can also be considered and reviewed. In addition, it is also important to know more about the customer persona so that campaign programs are more targeted.
