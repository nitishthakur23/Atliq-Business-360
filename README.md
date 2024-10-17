# Business Insights 360

## Project Overview

AtliQ Hardware has been experiencing rapid growth and, to stay ahead of the competition, they've decided to adopt Power BI as their first data analytics tool. The goal is to harness the power of data for better decision-making across various business units, including finance, sales, marketing, and supply chain management. This project is designed to provide key insights to stakeholders across all these areas, ensuring that the company stays competitive.
![Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiZTdhYzA3OWYtYzE4MS00ZTEzLWJmYzgtNmI0ZjEwN2Q3ODBkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech stacks

- SQL
- PowerBi Desktop
- Excel
- DAX language
- DAX Studio (for report optimization)
- Project Charter

## Power BI Techniques Learned

- Key questions to ask before starting a project
- Creating calculated columns
- Building measures using DAX
- Data modeling principles
- Using bookmarks to toggle between visuals
- Page navigation using buttons
- Error handling with the `DIVIDE` function to avoid zero division
- Creating a custom date table using M language
- Dynamic titles based on filters
- KPI indicators
- Conditional formatting with icons and background colors
- Data validation techniques
- Publishing reports to Power BI Service
- Setting up auto-refresh using a personal gateway
- Creating a Power BI App
- Collaboration, workspace, and access management in Power BI Service

## Company Background

AtliQ Hardware has grown significantly and now operates globally, selling computers and accessories through various channels:
 
- Retailers
- Direct sales
- Distributors
  
Recently, the company experienced unforeseen losses after opening a store in America based on surveys and intuition rather than data. Competitors, with their data analytics teams, have been outperforming them. As a result, AtliQ decided to form its own analytics team to drive decisions through data-driven insights.

## Business related terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGC - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

Recently, the company experienced unforeseen losses after opening a store in America based on surveys and intuition rather than data. Competitors, with their data analytics teams, have been outperforming them. As a result, AtliQ decided to form its own analytics team to drive decisions through data-driven insights.

## Dataset Understanding
### Note: The dataset is not publicly available because of the restriction by the owner.
Understanding the data is crucial before starting the analysis. Here's a breakdown of the data used in the project:

### **gdb041 Database**:
- **dim_customer**: Contains customer data from 27 markets and 75 customers. Sales channels include retailers, direct, and distributors.
- **dim_market**: Information on markets, sub-zones, and regions (APAC, EU, NA, LATAM).
- **dim_product**: Product categories, divisions (Peripherals, Accessories, Networking, Storage), and product variants.
- **fact_forecast_monthly**: Contains customer demand forecasts.
- **fact_sales_monthly**: Similar to the forecast table but holds actual sales data.

### **gdb056 Database**:
- **freight_cost**: Contains travel and other costs for each market.
- **gross_price**: Records product gross prices.
- **manufacturing_cost**: Manufacturing cost details.
- **pre_invoice_deductions**: Pre-invoice deduction percentages for each customer.
- **post_invoice_deductions**: Details of post-invoice deductions.

## Importing data into PowerBi

- As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential

## Data Model

- Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
- Poor data modeling affects the over all performance of the report.
- Following Good practices of data modeling is must. Refer this page to get to know the good practices.
- In this project, we have followed Snowfall data modeling method.


### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

## Home view

In Home view, all the views button will be available. User will land on specific view page by clicking the button 

- Info
- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View
- Products
- Support


## Home Page

![Home](https://github.com/nitishthakur23/Atliq-Business-360/blob/main/Images/Home.png)

## Finance View

![Finace.gif](https://github.com/nitishthakur23/Atliq-Business-360/blob/main/Images/finance.png)
## Sales View

![Sales.gif](https://github.com/nitishthakur23/Atliq-Business-360/blob/main/Images/Sales.png)

## Marketing View

![Marketing.gif](https://github.com/nitishthakur23/Atliq-Business-360/blob/main/Images/Market.png)

## Supply chain View

![Supply chain.gif](https://github.com/nitishthakur23/Atliq-Business-360/blob/main/Images/Supply.png)

## Executive View

![Executive.gif](https://github.com/nitishthakur23/Atliq-Business-360/blob/main/Images/Excecutive.png)

## Trends

![Trends](https://github.com/nitishthakur23/Atliq-Business-360/blob/main/Images/trends.png)

you can find the full report file here : ![Report](https://github.com/nitishthakur23/Atliq-Business-360/blob/main/Dashboard/Project(Business%20360).pbix)


## Project Outcome

By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.
