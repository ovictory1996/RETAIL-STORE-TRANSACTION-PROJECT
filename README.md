# RETAIL-STORE-TRANSACTION-PROJECT

![RETAIL_STORE](RETAIL.jpeg)

## TABLE OF CONTENT

- [INTRODUCTION](#Introduction)

- [DATA DESCRIPTION](#Data-Description)

- [Data Collection and Preparation ](#Data-Collection-and-Preparation)

- [Data Analysis](#Data-Analysis)

- [Skills demonstrated](#Skills-demonstrated)

- [Visualizations](#Visualizations)

- [Insight from analysis](#Insight-from-analysis)

- [Summary of Analysis](#Summary-of-Analysis)

- [Conclusion](#Conclusion)

## INTRODUCTION
This project focuses on the analysis of a retail sales dataset using Microsoft Excel and Power BI. The dataset contains information such as transaction dates, customer IDs, product categories, stock keeping units (SKUs), quantities sold, and sales amounts. Before analysis, the data was cleaned and transformed in Microsoft Excel to ensure accuracy, consistency, and reliability. This process involved removing duplicates, handling missing values, correcting data formats, and creating additional fields such as Year, Month, Day, and Total Revenue.
After the cleaning and transformation process, the dataset was imported into Power BI for visualization and analysis. Interactive dashboards were developed to monitor key performance indicators (KPIs), including total Sales, total customers, and quantity sold. Various charts were used to explore sales trends, 20 top-performing Customer_id and Monthly sales trends.The primary objective of this project is to demonstrate how business intelligence tools can transform raw sales data into meaningful insights that support strategic decision-making and business growth.

## Data-Description
The data is structured in a tabular format where each row represents a single transaction made by a customer on a specific date. It is designed to support sales analytics such as revenue tracking, customer behavior analysis, and product performance evaluation.
- Date – The exact date the transaction occurred
- Customer_ID – Unique identifier for each customer
- Transaction_ID – Unique ID for each sales transaction
- SKU_Category – Product category code
- SKU – Unique product identifier
- Quantity – Number of items purchased per transaction
- Sales_Amount – Revenue generated per item/transaction line
- Year – Year extracted from the date (e.g., 2016)
- Month – Month extracted from the date (e.g., January)

## Data Collection and Preparation 
#### Raw data:
The dataset on Retail Store Transaction was obtained from Kaggle.
[Download Retail Store Transcation](Retail_raw_data.xlsx)

### Tools used: 
        - Excel 
        - Powerbi
## SKILLS DEMONSTRATED:
 - Excel:
    - The first column, which contains the row numbering, was removed because it is not necessary for the analysis.
    - convert it as a Table
    - Remove the duplicates
    - creating a new Column for Year, Month, Day and Total REvenue

 - Powerbi:
     - importing the dataset from the excel
     - creating the measures using DAX (Data Analysis Expressions) to perform dynamic calculations. These measures included Total customer, Total sales and Total quantity.
  
      - Data visualization 
      - Dashboard development 
      - Insight Generation
  
  ### Data Analysis:
  - Top 20 Sum of Sales_Amount by Customer_ID
  - Sum of Total_Revenue by Day
  - Total_Revenue by Month

## Visualizations:
       - To better understand sales performance, customer purchasing behavior, and revenue trends, the dataset was first cleaned and transformed in Microsoft Excel before being imported into Power BI for analysis and visualization. Several interactive dashboards and visualizations were created to provide meaningful insights into the sales transactions recorded in the dataset.
The visualizations developed include:
            - Line Charts (Trend Analysis): Used to analyze total revenue trends over Month
            - Column Chart: It provides insight into daily sales performance, highlights the highest and lowest revenue-generating days
            - Waterfall Chart: This visualization displays the cumulative contribution of the top 20 customers based on total sales amount.
            - Cards/KPI Visualizations: Used to present important measures such as Total Revenue Total Customers, and Total Quantity Sold.









