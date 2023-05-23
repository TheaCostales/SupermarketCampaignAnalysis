## Problem Statement – Supermarket Campaign Analysis
* ABC Supermarket is planning for the year-end sale - they want to launch a new offer i.e. gold membership for only $499 that is of $999 on normal days(that gives 20% discount on all purchases) only for existing customers, for that they need to do a campaign through phone calls - the best way to reduce the cost of the campaign is to make a predictive model to classify customers who might purchase the offer, using the data they gathered during last year's campaign.


* We will build a model for classifying whether customers will reply with a positive response or not.

**Problem:**
* The data-set aims to answer the following key questions:
What are the different factors which affect the target variable?
* How can we improve model performance using hyperparameter tuning and prevent data leakage using pipelines while building a model to predict the response of a customer? 
What business recommendations can we give based on the analysis?

**Data Dictionary:**

The data contains characteristics of the people
- Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise
- Complain - 1 if a customer complained in the last 2 years
- DtCustomer - date of customer’s enrolment with the company
- Education - customer’s level of education
- Marital - customer’s marital status
- Kidhome - number of small children in customer’s household
- Teenhome - number of teenagers in customer’s household
- Income - customer’s yearly household income
- MntFishProducts - the amount spent on fish products in the last 2 years
- MntMeatProducts - the amount spent on meat products in the last 2 years
- MntFruits - the amount spent on fruits products in the last 2 years
- MntSweetProducts - amount spent on sweet products in the last 2 years
- MntWines - the amount spent on wine products in the last 2 years
- MntGoldProds - the amount spent on gold products in the last 2 years
- NumDealsPurchases - number of purchases made with discount
- NumCatalogPurchases - number of purchases made using catalog
- NumStorePurchases - number of purchases made directly in stores
- NumWebPurchases - number of purchases made through the company’s web site
- NumWebVisitsMonth - number of visits to company’s web site in the last month
- Recency - number of days since the last purchase
- ID - unique customer-id
- Year_Birth - customer's year of birth
