# Business Insights 360

## Project Overview

The project is an end-to-end Data analysis of the key performance indicators of various departments in a Hardware Manufacturer. AtliQ Hardware has been growing rapidly in recent years. As a result, they have decided to implement data analytics using PowerBi in their company for the first time to surpass their competitors in the market and make data-driven decisions. In addition, this project hoped to answer stakeholder questions about all aspects like finance, sales, marketing, and supply chain.
I worked on this project by following the Codebasics PowerBi Course; the link to the course is [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)

## Technical Skills learnt from this Project

- SQL
- PowerBi Desktop
- Excel
- DAX language
- Power Query
- DAX studio (for optimizing the report)
- Project charter file (Mural)

## PowerBI techniques Learnt

- What are all the questions that should be asked before starting the project
- Creating calculated columns
- Creating measures using the DAX language
- Data modeling
- Creating a Dynamic Table using DAX
- Learnt about a few DAX formulas (SUMX(), CALCULATE(),SAMEPERIODLASTYEAR(), SWITCH(), IF(), ALLNOBLANKROW()).
- Utilized the DIVIDE function to prevent zero-division errors
- Creating data table using m language
- Dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting of the values in visuals using icons or background 	color
- Data validation techniques
- PowerBi services

## Business related terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGC - cost of goods sold
- Absolute Net Error - Absolute Net error is the absolute aggregated sum of all the deviations from Actual and Forecasted data.
- Forecast Accuracy - Forecast accuracy is the degree to which someone predicts sales.

### Questions to ask before starting with dashboard

- What is the objective of building this PowerBi dashboard?
- In what terms the success of this project will be measured?
- What will be the time deadline for the project?
- What are all the hopes stakeholders have out of this project?
- what are all stakeholders' fears about building this dashboard?
- Who will be using this dashboard, and for what purpose?
- What are all expectations the stakeholders have by completing this project?
- What can go wrong while building this project?
- What are all the resources/ data needed to build this dashboard?
- Is there any input from stakeholders regarding the design and views of the dashboard?

### Dataset

Fact table: A fact table holds the data to be analyzed.

Dimension table: This table stores data about how the data in the fact table can be analyzed. 

- gdb041:
    - dim_customer
        - **27** distinct markets (ex India, USA, spain)
        - **75** distinct customers thorough out the market
        - **2** types of platforms
            - Brick & Motors - Physical/offline store
            - E-commerce - Online Store (Amazon, flipkart)
        - Three channels
            - Retailer
            - Direct
            - Distributors
    - dim_market
        - **27** distinct markets (ex India, USA, spain)
        - 7 sub-zones
        - 4 regions
            - APAC
            - EU
            - nan
            - LATAM
    - dim_product
        - Divisions
            - P & A
                - Peripherals
                - Accessories
            - PC
                - Notebook
                - Desktop
            - N & S
                - Networking
                - Storage
        - There are 14 different categories, Like Internal HDD, keyboard
        - There are different variants available for the same product
    - fact_forecast_monthly
        - This table is used to forecast the customer’s need in advance, which can help in
            - Higher customer satisfaction
            - Reduced cost in warehouses for storage purpose
        - The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
        - All the date of the month will be replaced by the start date of the month
        - It will have all the column names and in the end it will have the forecast quantity need of the customer
    - fact_sales_monthly
        - This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.
- gdb056
    - freight_cost
        - This table has details of travel cost and other cost for each market with fiscal year
    - gross_price
        - Has the details of gross prices with product code
    - manufacturing_cost
        - Has the details of manufacturing cost with product code with year
    - Pre_invoice_dedutions
        - Has the details of pre invoice deductions percentage for each cutomer with year
    - Post_invoice_deductions
        - Post invoice deductions and other deductions details

## Importing data into PowerBi

- As the database is MySQL in this project, we need to import the datasets from the Mysql database to PowerBi by providing the Database access credential.

## Data Model

- Following Good practices of data modeling is a must. [Blog](https://addendanalytics.com/blog/data-modelling-best-practices/)
- In this project, we have followed mix of STAR and Snowflake data modeling method.

<img src="https://github.com/Naveen-S6/Business_Insights_360/blob/main/Resources/Data_model.png" class="center">

### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required




## Info Page

![Info.gif](https://github.com/Naveen-S6/Business_Insights_360/blob/main/Resources/Info.gif)

## Finance View

![Finace.gif](https://github.com/Naveen-S6/Business_Insights_360/blob/main/Resources/Finace.gif)
## Sales View

![Sales.gif](https://github.com/Naveen-S6/Business_Insights_360/blob/main/Resources/Sales.gif)

## Marketing View

![Marketing.gif](https://github.com/Naveen-S6/Business_Insights_360/blob/main/Resources/Marketing.gif)

## Supply chain View

![Supply chain.gif](https://github.com/Naveen-S6/Business_Insights_360/blob/main/Resources/supply%20chain.gif)


## Project Outcome


