# Data-Warehouse-and-Sales-Data-Mart-Analysis

# SalesDataMart
Building Sales Data Mart Using SSIS
# What is a data mart ?
A Data Mart is focused on a single functional area of an organization and contains a subset of data stored in a Data Warehouse. A Data Mart is a condensed version of Data Warehouse and is designed for use by a specific department, unit or set of users in an organization. E.g., Marketing, Sales, HR or finance. It is often controlled by a single department in an organization.

## Project Overview
*	1-Developed a data warehouse, pipelining data from SQL Server using SQL Server Integration Services (SSIS).
*	2-Designed star schema dimensional model on the data warehouse, loading facts and dimensions (Data Modeling).
*	3-Implemented OLE DB Source, Data Conversion, Slowly Changing Dimensions and Derived Column Full load and Incremental load.
*	4-Built Visual dashboards and improved Sales report for sales managers using PowerBI.

## Data Sources
### AdventureWorks2019 (OLTP) from Microsoft https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms

  - Customer
  - Product
  - SalesTerritory
  - SalesOrderHeader  
  - SalesOrderDetail
  - Person
  - ProductModel
  - ProductModelProductDescriptionCulture
  - ProductDescription
  - Production
  - ProductSubcategory

### EO_AdventureWorksDW2019 (DWH)

  - dim_customer
  - dim_date  
  - dim_territory
  - dim_product 
  - lookup_country
  - meta_control_table
  - fact_sales  

## Using ETL Tools
- SSIS SQL Server Integration Services
- SQL Server 
- C# Language 
- Data Modeling (SQL)
- Power BI

## Project Steps
# Step 1
1- Developing a Data Warehouse
1- <B>Data Modeling (Star Schema)</B>

![Capture](https://user-images.githubusercontent.com/90741989/205361677-9809f5c6-23e8-4505-a043-ed3e0c220d97.PNG)

# Implementing ETL
1- <B>Slowly Changing Dimension (SCD)</B>

![1-Slowly Changing Dimension (SCD)](https://user-images.githubusercontent.com/114536072/206842283-ef3e8641-d906-47f3-9611-74156df2712d.png)


2- <B>Full load </B>

![2-Full Load](https://user-images.githubusercontent.com/114536072/206842297-3f10a6dd-decf-4369-9f84-e35f76958535.png)

3- <B>Incremental load</B>

![3-Incremental Load](https://user-images.githubusercontent.com/114536072/206842315-1e498732-4073-4b10-951d-eb2bfa924782.png)

![4-Incremental Load](https://user-images.githubusercontent.com/114536072/206842327-cf7261a0-fd54-4a80-b1cb-704f5968b3bc.png)

##	4- Building Visual dashboards

### 2- Sales Management Dashboard

<B>The finished sales management dashboard with one page works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customer, and per product.</B>

<B>You can check the dashboard and try it out!</B>(https://app.powerbi.com/groups/me/reports/7251820f-0346-4bdc-8d17-ed56e29fbeb5/ReportSection)

<B>You can check my Portfolio and try discover other dashboards!</B>(https://yehiakhaledabouzeid.wordpress.com/)

![04 5-Sales Overview](file:///H:/Excel/SQL/200991713-6a5d8688-e3d1-422c-b7ca-2a3c634c7142.png)
