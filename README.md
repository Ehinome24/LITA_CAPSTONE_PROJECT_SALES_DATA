# LITA_CAPSTONE_PROJECT_SALES_DATA
This is my capstone project on sales data while learning Data Analysis with the Incubator Hub
## Project Title: Sales Data Analysis
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
In the initialphase of data cleaning and preparations, we performed the following actions;
- Data Loading and Inspection
- Handling Missing Variables
- Handling duplicates
- Data cleaning and formating

### Exploratory Data Analysis
---
This step involved the exploration of our dataset to answer some questions such as;
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

