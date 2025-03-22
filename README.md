**Credit Card Financial Report - SQL-Driven Real-time Dashboard**

**Project Overview**

The Credit Card Financial Report project focuses on leveraging SQL Server for robust data management and real-time insights generation. The project involves extracting, transforming, and analyzing financial transaction data from a credit card company to create a dynamic, interactive dashboard in Power BI.

**Tools & Technologies Used**

  •	SQL Server Management Studio (SSMS) – Data storage, indexing, querying, and relationship management
  •	Power Query (Excel) – Data preprocessing and transformation
  •	Power BI – Data visualization, real-time insights, and DAX calculations
  •	Excel – Initial data formatting and cleansing
  •	DAX (Data Analysis Expressions) – Advanced calculated measures and columns

**Data Processing Workflow**

  1. Data Extraction & Cleaning
    •	The dataset comprises two CSV files:
        o	customer.csv (Customer details)
        o	credit_card.csv (Credit card transactions)
    •	Data preprocessing in Power Query (Excel):
        o	Identifying and handling missing values
        o	Standardizing formats (dates, categorical values)
        o	Removing duplicates and ensuring consistency
  
  2. SQL Database Setup & Data Loading
    •	Tables Created in SQL Server:
      o	customers (Customer demographic and financial details)
      o	transactions (Credit card transactions)
    •	Importing Data into SQL:
      o	Used SSMS Import and Export Wizard to load CSV files into SQL tables.
      o	Ensured data integrity using primary keys and foreign keys.
      o	Indexed key columns (client_id) to optimize query performance.
     
  4. Data Modeling & Relationships in SQL
    •	Established a one-to-many relationship between customers and transactions using the client_id column.
    •	Executed SQL JOIN queries to merge customer and transaction data for deeper insights.
    •	Performed aggregations using GROUP BY to analyze customer spending behavior.
  
  5. Real-time Power BI Integration
    •	Connected SQL Server to Power BI using DirectQuery for real-time updates.
    •	SQL Views were created for efficient data retrieval.
  
  6. Advanced Data Analysis Using SQL & DAX
  
  7. Real-time Dashboard Components
    •	Cards: KPIs such as Total Revenue, Total Transactions, Total Income, Customer satisfaction score, transaction count, etc.
    •	Slicers: Filters for customer demographics, transaction dates, regions.
    •	Action Buttons: To reset filters in dashboard.
    •	Charts & Graphs
  
  8. Real-time Data Updates
    •	Additional data was inserted into SSMS tables, and Power BI automatically reflected these updates, demonstrating the power of DirectQuery.
  
**Key Insights Derived**
  •	Customer Segmentation: Identified high-spending customers and behavior patterns.
  •	Revenue Trends: Analyzed weekly, monthly and yearly transaction volume and revenue growth.
  •	Geographic and demographic Trends: Mapped revenue contributions from different locations, gender, profession, etc.
  •	Credit Utilization Analysis.

**Future Enhancements**
  •	Implementing stored procedures for automated reporting.
  •	Enhancing SQL queries with window functions for deeper trend analysis.
  •	Integrating Power Automate for scheduled data refresh.

**Conclusion**
This project demonstrates SQL-driven data analytics by efficiently storing, processing, and analyzing financial transactions, ultimately enabling real-time business intelligence through Power BI.
________________________________________
**Author: Prabhat Kumar**
**GitHub: prabhat-4539**
Date: March 2025





