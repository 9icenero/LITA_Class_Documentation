# LITA_Class-Documentation
This where I documented my first project while learning Data Analysis with the Incubator Hub.

## Project Title
International Brewies Yearly Sales Analysis

## Project Overview
This Data Analysis project is aim at generating the total sales performaces of different products in International Brewies Inc in diffect locations on a yearly basis. By analyzing the different parameters in the data received, we aim to seek the best performing product in different regions of the country and also the least performing product which will enable us to make insightfull decision when it comes to customer satisfaction.

##Table Outline for the Portfolio
Tools Used
Data Analysis
Data Visualization


## Tools Used
- Microsoft Excel [Download Here](https://www.Microsoft.com)
  1. For data cleaning
  2. For Analysis
  3. For Visualization.
     
- SQL - Structured Query Language for Quering of Data

- GitHub for Potfolio

## Data Analysis
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
#### Sales Per Year
![image](https://github.com/user-attachments/assets/51ac2700-21e7-4cc4-93a7-517c59539d18)

#### Company Products

![image](https://github.com/user-attachments/assets/3990faa4-fb55-419f-9df8-75c85a3eed4c)
