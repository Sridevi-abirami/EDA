# Customer Churn Analysis
Introduction:
This repository holds an end-to-end analysis on Customer Churn Analysis in Telecom Market. It provides insights, identifies KPI’s and suggests recommendations on how to reduce the overall churn rate with the analysis carried out on 7048 records with 21 columns. 

Dataset:
 The dataset used is Customer_churn.csv

Data Cleaning and Transformation:
The data from the data source is first checked for discrepancies. The NULL values can be imputed using mean/median /mode, whichever is appropriate. In this case, as the null values are less than 15%, it is removed from the total charges column. Then the tenure column is converted into bins to get a range of values column. The columns column id and tenure are removed as it will not be useful in the analysis. Now the data is transformed properly into the form that is ready for analysis. The overall churn rate is calculated as 26.5%, the analysis is done on the basis to reduce the 

Univariate Analysis: 
     The categorical columns of the customer churn table are analyzed with the churn category to identify the KPI’s for reducing the churn rate. 

Bivariate Analysis:
The entire records are grouped into active and churned customers and based on these two data frames, the bivariate analysis is done between the two columns of the query table to identify the factors that increase the churn rate of customers. The following graphs are generated in the bivariate analysis.
  
Numerical Analysis:
The lmplot is generated between the total charges and monthly charges to identify the relationship between them.
Kde plot is generated for monthly charges and the total charges to identify the density of the factors.
                                  
Conclusion:
 The following analysis is based on the overall churn rate of the customers that rate to 26.5%
1.	The senior citizens and female non-senior citizens who are without partners and non-dependents are high churners.
2.	Customers without device protection, Online security, online backup, tech support, multiple lines together with female customers with multiple lines and phone services are high churner.
3.	Customers with fiber optics Internet services, streaming movies plan and with or without streaming TV options are high churners.
4.	Customers who belong to the tenure group of 1-24, with Month-to-Month contract type, Electronic check payment and paperless billing are the high churners
5.	The high churners are those with high monthly charges in the range of 60 𝑡𝑜 120.
6.	The high churners seem to be the customers whose total charge is in the range of 0 to 2000; Maybe they are the ones who churn in a short period of time, so their total charges are less.
