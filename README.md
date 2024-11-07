# LITA_CAPSTONE_PROJECT_SALES_DATA
This is my capstone project on sales data while learning Data Analysis with the Incubator Hub
## Project Title: Sales Performance Analysis for a Retail Store 

[Project Overview](#project-overview)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualisation](#data-visualization)

[Analysis Results](#analysis-results)

[Recommendations](#recommendations)

### Project Overview
---
This Data Analysis project aims to uncover key insights on the sales performance of the retail store over a period of 20 months(1 year and 8 months). By analysing the various parameters in the provided data, we will be able to make reasonable and informed decisions which will enable us tell compelling stories around our data from the insight gotten and to know the performance of the retail store.

### Tools Used
---
- Microsoft excel for data cleaning, analysis and data visualization
- SQL- Structured Query Language for Data Query
- PowerBI for Data cleaning and data visualization
- Github for Portfolio Building

### Data Cleaning and Preparation
---
In the initialphase of data cleaning and preparations, I performed the following actions;
- Data Loading and Inspection
- Handling Missing Variables
- Handling duplicates
- Data cleaning and formating

### Exploratory Data Analysis
---
This step involved the exploration of the dataset to answer some questions such as;
- Top selling Products
- Regional Performance
- Monthly Sales Trends

### Data Analysis
---
These were some basic lines of code or queries used during the analysis;

```SQL
select Product, SUM(revenue) as total_sales from [dbo].[Sales Data]
group by product

select * from [dbo].[Sales Data]

AVERAGEIF(Table1[Product],C12,Table1[Revenue])

SUMIF(Table1[Region],D8,Table1[Revenue])
```

### Data Visualization
---

![sales data](https://github.com/user-attachments/assets/9834439b-8db5-4840-aa06-0a4b33e70fb2)

![Sales data pivot](https://github.com/user-attachments/assets/14e2a391-f865-4290-9cbe-0fcf939d98f3)

![top 5 cust  by total purchase amt](https://github.com/user-attachments/assets/eebc0a64-69a3-400a-af98-d30e90622935)

![Sales data Visual](https://github.com/user-attachments/assets/b325070a-1d34-41b9-b008-bb7d51ab0f75)


### Analysis Results 
---
The results of the analysis are summarized as follows;
1. The highest revenue was generated in the south with over 40% of the total revenue generated there.
2. Shoes generated the highest revenue although hats had the highest number of sales
3. February 2024 recorded the highest sales value and april 2023 had the lowest sales value

### Recommendations 
---
- Since there is a higher increase in sales in February (both 2023 and 2024), promotions should be done during that period to maximize sales
- In areas with low sales values, advertisements should be carried out with discounts given when and where necessary
- More focus should be placed in the Southern region and sales strategies should be improved in other regions.

























