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

# Step 2 
![Screenshot (85)](https://user-images.githubusercontent.com/105324794/201488462-3e789928-c9b1-4789-bf07-46831e00d58b.png)

#  Step 3 

![Screenshot (86)](https://user-images.githubusercontent.com/105324794/201488472-da7f656d-e61c-4c3d-9bf8-d9776178f329.png)

# Step 4
![Screenshot (87)](https://user-images.githubusercontent.com/105324794/201488529-0cd45225-b4c0-4937-b4e7-e2c84e721ced.png)

# Step 5-1- Fact Table 

![Screenshot (88)](https://user-images.githubusercontent.com/105324794/201488545-7f80718c-8526-4360-8273-bdc0c84253b9.png)

# Step 5-2   Fact Table 

![Screenshot (89)](https://user-images.githubusercontent.com/105324794/201488588-5501e4e3-619e-4d7f-8671-634a6426620f.png)

3- Implementing ETL
1- <B>Slowly Changing Dimension (SCD)</B>

![03 1-Slowly Changing Dimension (SCD)](https://user-images.githubusercontent.com/114536072/206842283-ef3e8641-d906-47f3-9611-74156df2712d.png)


2- <B>Full load </B>

![03 2-Full Load](https://user-images.githubusercontent.com/114536072/206842297-3f10a6dd-decf-4369-9f84-e35f76958535.png)

3- <B>Incremental load</B>

![03 3-Incremental Load](https://user-images.githubusercontent.com/114536072/206842315-1e498732-4073-4b10-951d-eb2bfa924782.png)

![03 3 01-Incremental Load](https://user-images.githubusercontent.com/114536072/206842327-cf7261a0-fd54-4a80-b1cb-704f5968b3bc.png)

##	4- Building Visual dashboards

### 1- Data Model

<B>Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI after exporting the DWH into CSV files.</B>

<B>The queries used to extract data into CSV files are in the folder [04.1-To extract data to CSV Files].</B>

<B>This data model also shows how FACT_Budget has been connected to FACT_InternetSales and other necessary DIM tables.</B>

![04 4-Moadel Tables](https://user-images.githubusercontent.com/114536072/206843284-0599903c-c61d-4b6a-be99-b012fe096e17.png)

### 2- Sales Management Dashboard

<B>The finished sales management dashboard with one page works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customer, and per product.</B>

<B>You can check the dashboard and try it out!</B>(https://app.powerbi.com/groups/me/reports/7251820f-0346-4bdc-8d17-ed56e29fbeb5/ReportSection)

<B>You can check my Portfolio and try discover other dashboards!</B>(https://yehiakhaledabouzeid.wordpress.com/)

![04 5-Sales Overview](https://user-images.githubusercontent.com/114536072/206843418-556c0316-c9aa-4613-9713-1abd6f85ac1f.jpg)

