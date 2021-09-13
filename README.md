# Introduction
Customer churn refers to the percentage of customers who have stopped using a company's product or services. This is a concern for every business. In this project,
we have conducted some exploratory data analysis, hypothesis testing, and predicted customers more prone to getting churned based on the customer and the credit card consumption attributes.

## Data Source
We have taken an open dataset from kaggle https://www.kaggle.com/sakshigoyal7/credit-card-customers.

## Data Description
The dataset consists of information about 10,127 customers with some demographic information (e.g., gender, age, marital status, education level, number of dependents, salary), 
banking and credit card information (e.g., credit card limit, card category, revolving balance, period of contact with the bank, period of inactivity, etc). 
The dataset has 21 columns including 19 features, one column with the client identification number, and another column marking their attrition status (whether the customer is existing or attrited).

## Variable Description
The dataset has 21 variables in total. A short description of the variables is given below-

'CLIENTNUM': Unique identifier for the customer holding the account  
'Attrition_Flag': Internal event (customer activity) variable -Existing customer, Attrited customer. This is the target variable of our data.  
'Customer_Age': Customer's Age in Years.  
'Gender': M=Male, F=Female.  
'Dependent_count': Number of dependents.  
'Education_Level': Educational Qualification of the account holder (example: high school, college, graduate, etc.)  
'Marital_Status': Married, Single, Divorced, Unknown.  
‘Income_Category’: Annual Income Category of the account holder (Less than 40k, $40k - $60k, $60k - $80k, $80k – 120k, $120k above, Unknown)  
'Card_Category': Type of Card (Blue, Silver, Gold, Platinum)  
'Months_on_book': Period of relationship with the bank.  
'Total_Relationship_Count': Total no. of products held by the customer.  
'Months_Inactive_12_mon': No. of Months  inactive in the last 12 months.  
'Contacts_Count_12_mon': No. of Contacts in the last 12 months.  
'Credit_Limit': Credit Limit on the Credit Card.  
'Total_Revolving_Bal': Total Revolving Balance on the Credit Card.  
'Avg_Open_To_Buy': Open to Buy Credit Line (Average of last 12 months)  
'Total_Amt_Chng_Q4_Q1': Change in Transaction Amount (Q4 over Q1).  
'Total_Trans_Amt': Total Transaction Amount (Last 12 months).  
'Total_Trans_Ct': Total Transaction Count (Last 12 months).  
'Total_Ct_Chng_Q4_Q1': Change in Transaction Count (Q4 over Q1).  
'Avg_Utilization_Ratio': Average Card Utilization Ratio.  