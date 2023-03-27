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
##	1- Developing a Data Warehouse
1- <B>Data Modeling (Star Schema)</B>

![Capture](https://user-images.githubusercontent.com/90741989/205361677-9809f5c6-23e8-4505-a043-ed3e0c220d97.PNG)

