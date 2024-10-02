# LITA_Class_Documentation
This where I documented my first project while learning Data Analysis with the Incubator Hub.



### Project Title
---
**International Brewies Yearly Sales Analysis**


### Table Outline for the Portfolio
---
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparations](#data-cleaningand-preparation)
- [Data Analysis](#data-analysis)
- [Data Visualization](#data-visualization)
- [Conclusion](#conclusion)
- [Recommedndation](#recommendation)

### Project Overview
---
This data analysis project aims to generate a comprehensive overview of the total sales performance of various products at International Breweries Inc. across different locations on a yearly basis. By analyzing the various parameters in the collected data, we seek to identify the best-performing products in different regions of the country as well as the least-performing ones. This analysis will enable us to make informed decisions to enhance customer satisfaction.

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
#### *Sales Per Year*
![image](https://github.com/user-attachments/assets/51ac2700-21e7-4cc4-93a7-517c59539d18)

#### _Company Products sales in the year 2019_

![image](https://github.com/user-attachments/assets/3990faa4-fb55-419f-9df8-75c85a3eed4c)

### Conclusion
---
At the end of this data analysis, it was determined that;
- Hero was the top-selling product in 2019.
- Grand Malt recorded the lowest sales.

### Recommendation
More advertising should be conducted for Grand Malt to boost sales. Additionally, a feedback form should be provided to customers to rate the product's taste, price, and other factors. This will help in improving the product.
