# FlexiMart Data Architecture Project
Student Name: Bharadwaj  
Student ID: 25071962    

# Project Overview :
This project implements an end-to-end data architecture solution for FlexiMart, an e-commerce company.  
The project covers data ingestion from raw CSV files, data cleaning and loading into a relational database, NoSQL analysis using MongoDB, and analytical reporting using a data warehouse.

# What This Project Contains :
- ETL pipeline to clean and load raw CSV data into MySQL
- Database schema documentation and business SQL queries
- NoSQL (MongoDB) analysis with practical operations
- Data warehouse design using star schema
- OLAP analytical queries for business reporting

# Repository Structure :
- `data/` → Raw CSV input files  
- `part1-database-etl/` → ETL pipeline, schema docs, SQL queries  
- `part2-nosql/` → MongoDB analysis and operations  
- `part3-datawarehouse/` → Star schema, warehouse data, analytics queries  

# Technologies Used :
- Python 3.x  
- MySQL  
- MongoDB  
- Pandas  

# How to Run the Project :
1. Create MySQL databases:
   ```sql
   CREATE DATABASE fleximart;
   CREATE DATABASE fleximart_dw;
