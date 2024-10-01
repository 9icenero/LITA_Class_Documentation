# LITA_Class-Documentation-

## This where I documented my first project while learning Data Analysis with the Incubator Hub.
### Project Title: International Brewies Yearly Sales Analysis

## Tools Used
- Microsoft Excel [Download Here](https://www.Microsoft.com)
  1. For data cleaning
  2. For Analysis
  3. For Visualization.
     
- SQL - Structured Query Language for Quering of Data

- GitHub for Potfolio

Data Analysis
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

#Data Visualization

![image](https://github.com/user-attachments/assets/51ac2700-21e7-4cc4-93a7-517c59539d18)
