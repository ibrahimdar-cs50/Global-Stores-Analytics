# Global-Stores-Analytics
Data Analytical insights into store & order pattern of an e-commerce store.
Objectives:
1. Identified which products to buy more or less of as per inventory available, product wise demand and vendor availability and geographical location.
2. Quarterly profit margin projections product wise.
3. Maintenance of Master Database.


Assumptions:
- Office is identified as distribution centre
- Orders shipped from Australia for APAC countries.
-  Orders shipped from UK & France for EMEA countries.
-  Orders shipped from Japan for Japan & APAC countries.
-  Order shipped from USA for USA and Canada.

  Step 1: All the columns in each table were checked to eliminate any wrong entries and make database hygenic.
  Step 2: Relationships between different entities were assessed keeping in mind the business logic and edits/changes were made whereever necessary.
  Step 3: Added new rows, transferred values from one table to another using primary keys for easy joins.
  Step 4: Tables were updated by adding new columns, modifying columns, deleting irrelevant data etc.
  Step 5: Master Table was then created named as ****orderdetails*** which included all the columns that were necessary for us to acheive our data analysis objectives.
  Step 6: Relationships between different columns in orderdetails table were validated again to ensure data integrity.
  Step 7: Select, orderby,groupby,count,sum,avg,sumifs, etc. operators were used to pull data as per our requirement.
  
