# LITA_Class-Documentation
This where I documented my first project while learning Data Analysis with the Incubator Hub.

### Project Title
---
International Brewies Yearly Sales Analysis

### Table Outline for the Portfolio
---
- [Project Overview].(#project overview)
- Data Sources
- Tools Used
- Data Cleaning and Preparations
- Data Analysis
- Data Visualization

### Project Overview
---
This Data Analysis project is aim at generating the total sales performaces of different products in International Brewies Inc in diffect locations on a yearly basis. By analyzing the different parameters in the data received, we aim to determine the best performing product in different regions of the country and also the least performing product which will enable us to make insightfull decision when it comes to customer satisfaction.

### Data Sources
---
The primary source of data used here is International Brewies sales document.CSV. This will be made available for view.

### Tools Used
---
- Microsoft Excel [Download Here](http://mxj6.2.vu/2)
  1. For data cleaning
  2. For Analysis
  3. For Visualization.
     
- SQL - Structured Query Language for Querying of Data
- GitHub for Portfolio Building

### Data Cleaning and Preparations
----
In the initial phase of the data cleaning and preparations, we preform the following actions;
1.  Data inspection and loading
2.  Handling missing variables
3.  Data cleaning and formatting

### Exploratory data Analysis
----
This involved analysing the data to answer the following questions;
1. What is the overall sales trend in different years?
2. Which product is the best seller?
3. What product has the least sales?
4. Profit made in the year 2019 for different products.
   
### Data Analysis
---
```SQL
SELECT SUM(profit) AS TOTALPROFITS
FROM [dbo].[International Breweries]
WHERE years = '2017';

SELECT MAX(profit) AS MaxProfit
FROM [dbo].[International Breweries]
WHERE Brands = 'Trophy'
AND Years = '2018';

Select min(Profit) as min_Profit  from [dbo].[International Breweries]
Where Years = '2018';
```

### Data Visualization
---
#### Sales Per Year
![image](https://github.com/user-attachments/assets/51ac2700-21e7-4cc4-93a7-517c59539d18)

#### Company Products sales in the year 2019

![image](https://github.com/user-attachments/assets/3990faa4-fb55-419f-9df8-75c85a3eed4c)

### Conclusion/Recommendation
---
At the end of this data analysis, it was determined that;
- Hero has a product has the highest sales in the year 2019.
- Grand malt has the least sales.

### Recommendation
More advert should be done for Grand malt inorder to boost sales. Also a feedback form should be given to customers to rate the products taste,price etc. This will help improve the products.
