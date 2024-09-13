# Ecommerce_Data_Engineering_Project
This repository contains an end to end data engineering project using : Micorsoft Azure Data Factory , Azure Data Lake Gen 2, Databricks, Synapse Analytics 


**Data Architecture :**

![image](https://github.com/user-attachments/assets/1ccb60b6-6989-494e-96d8-3df596dec695)


Insights and Recommendations : 

1) Perfomed **Engagement depth analysis** to segment customers into 3 categories. Most customers are occasional buyers or one time buyers with **regular customers only at 9.52 %**.<br />
  

2) **Decline in Monthly Customer Acquisition** : Decrease in New Customer acqusition rate over the course of time . From Acquiring 26 new customers in Mar 23 to 1 new customer in Feb 24. Indicating effectiveness or need of marketing campaigns and market expansion efforts<br />
   
3) Employed **LAG() window functions** to calculate the month on month percentage change in sales with  Feb-24 experiencng the largest sales percentage **decline of 75 %** from previous month.<br />
   
4) Evaluated product turnover rate to **optimize inventory restocking**, inducing a decrease in management cost.<br />
       Product 7 : Digital SLR Camera : 78<br />
       Product 3 : Bluetooth Headphones: 68<br />
       Product 5 : Laptop 15 Pro : 67<br />
   
5) Product Id 8 and Product Id 1 were bought by less than 40 percent of the customer base but generated the most sales revenue with average order quantity of 2, Indicating that they are **premium end products** that should be marketed extensively to increase profit and revenue.<br />
   

    
ADF Pipeline :<br />

https://adf.azure.com/en/authoring/pipeline/pipeline1?factory=%2Fsubscriptions%2F687d10a5-055c-41d7-b42d-1ffdc53181dd%2FresourceGroups%2Fecommerce_analytics%2Fproviders%2FMicrosoft.DataFactory%2Ffactories%2Fecommerceprakhar-df

![image](https://github.com/user-attachments/assets/473d6930-5ac5-4da0-8a6a-88d2fd050147)



Azure Databricks File :<br />

https://adb-2633106587622728.8.azuredatabricks.net/?o=2633106587622728#notebook/1071530084760765




Azure Synapse Analytics File :<br />

https://web.azuresynapse.net/authoring/analyze/sqlscripts/SQL%20script%201?workspace=%2Fsubscriptions%2F687d10a5-055c-41d7-b42d-1ffdc53181dd%2FresourceGroups%2Fecommerce_analytics%2Fproviders%2FMicrosoft.Synapse%2Fworkspaces%2Fecommerce-analytics-sa
