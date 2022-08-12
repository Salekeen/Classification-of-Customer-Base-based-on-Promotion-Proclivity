### Problem Statement

Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

### Content
Attributes

**People**

- ID: Customer's unique identifier - *Categotical*
- Year_Birth: Customer's birth year - *Categorical*
- Education: Customer's education level - *Categorical(Ordinal)*
- Marital_Status: Customer's marital status - *Categorical*
- Income: Customer's yearly household income - *Quantitative*
- Kidhome: Number of children in customer's household - *Categorical*
- Teenhome: Number of teenagers in customer's household - *Categorical*
- Dt_Customer: Date of customer's enrollment with the company - *Quantitative*
- Recency: Number of days since customer's last purchase - *Quantitative*
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise - *Categorical*

**Products**

- MntWines: Amount spent on wine in last 2 years - *Quantitative*
- MntFruits: Amount spent on fruits in last 2 years - *Quantitative*
- MntMeatProducts: Amount spent on meat in last 2 years - *Quantitative*
- MntFishProducts: Amount spent on fish in last 2 years - *Quantitative*
- MntSweetProducts: Amount spent on sweets in last 2 years - *Quantitative*
- MntGoldProds: Amount spent on gold in last 2 years - *Quantitative*

**Promotion**

- NumDealsPurchases: Number of purchases made with a discount - *Quantitative*
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise - *Categorical*
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise - *Categorical*
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise - *Categorical*
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise - *Categorical*
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise - *Categorical*
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise - *Categorical*

**Place**

- NumWebPurchases: Number of purchases made through the company’s website - *Quantitative*
- NumCatalogPurchases: Number of purchases made using a catalogue - *Quantitative*
- NumStorePurchases: Number of purchases made directly in stores - *Quantitative*
- NumWebVisitsMonth: Number of visits to company’s website in the last month - *Quantitative*


### Target
Need to perform clustering to summarize customer segments.