# Project: Marketing Campaigns

**Problem Scenario:**
Marketing mix is a popular concept used in implementing marketing strategies. It includes multiple areas of focus as part of a comprehensive marketing plan, which revolves around the four Ps of marketing: product, price, place, and promotion.

**Problem Objective:**
Gain a better understanding of the various factors that contribute to customer acquisition by performing exploratory data analysis and hypothesis testing.

**Data Description:**
The tabular data provided to the user includes variables related to the four Ps of marketing:

* **People:** birth-year, education, income, etc.
* **Product:** amount spent on wine, fruits, gold, etc.
* **Place:** sales channels, like websites, stores, etc.
* **Promotion:** promotions and results of different campaigns.

| Variable | Description |
|---|---|
| ID | Customer's unique identifier |
| Year of birth | Customer's year of birth |
| Education | Customer's highest level of education |
| Marital Status | Customer's marital status |
| Income | Customer's annual income |
| Kidhome | Number of children at home |
| Teenhome | Number of teenagers at home |
| Dt_Customer | Date the customer became a customer |
| Recency | Number of days since the customer's last purchase |
| MntWines | Amount spent on wine in the past year |
| MntFruits | Amount spent on fruits in the past year |
| MntMeatProducts | Amount spent on meat products in the last 2 years |
| MntFishProducts | Amount spent on fish products in the last 2 years |
| MntSweetProducts | Amount spent on sweet products in the last 2 years |
| MntGoldProds | Amount spent on gold products in the last 2 years |
| NumDealsPurchases | Number of purchases made through deals in the last 2 years |
| NumWebPurchases | Number of purchases made through the web in the last 2 years |
| NumCatalog Purchases | Number of purchases made through the catalog in the last 2 years |
| NumStorePurchases | Number of purchases made in stores in the last 2 years |
| NumWebVisitsMonth | Number of visits to the website in the past month |
| AcceptedCmp3 | 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise |
| AcceptedCmp4 | 1 if the customer accepted the offer in the 4th campaign, 0 otherwise |
| AcceptedCmp5 | 1 if the customer accepted the offer in the 5th campaign, 0 otherwise |
| AcceptedCmp1 | 1 if the customer accepted the offer in the first campaign, 0 otherwise |
| AcceptedCmp2 | 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise |
| Response | 1 if the customer accepted the offer in the last campaign, 0 otherwise |
| Complain | 1 if customer complained in the last 2 years |
| Country | Customer's country of residence |


## Tasks

### Stage 1: Data Preparation

* Import the data and investigate variables to check if they are imported correctly.
* Perform missing value imputation for income values.
* Clean the data, if necessary.
* Create variables to populate the total number of children, age, and total spending.

### Stage 2: Data Exploration

* Create box plots and histograms to understand the distributions and outliers.
* Perform outlier treatment.
* ~~Use ordinal encoding and one hot encoding according to different types of categorical variables.~~
* Create a heatmap to showcase the correlation between different pairs of variables.

### Stage 3: Hypothesis Testing

Test the following hypotheses:

* Older people are not as tech-savvy and probably prefer shopping in-store.
* Customers with kids probably have less time to visit a store and would prefer to shop online.
* Other distribution channels may cannibalize sales at the store.
* Does the US fare significantly better than the rest of the world in terms of total purchases?

### Stage 4: Data Visualization

Use appropriate visualization to help analyze the following:

* Which products are performing the best, and which are performing the least in terms of revenue?
* Is there any pattern between the age of customers and the last campaign acceptance rate?
* Which Country has the greatest number of customers who accepted the last campaign?
* Do you see any pattern in the no. of children at home and total spend?
* Education background of the customers who complained in the last 2 years.
