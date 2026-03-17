Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project 🚀
This project demonstrates an end-to-end data warehousing and analytics solution — from raw data ingestion to generating actionable business insights. It is designed as a portfolio project to showcase best practices in data engineering and data analytics.

🏗️ Data Architecture

This project follows the Medallion Architecture approach:
-Bronze Layer:
Stores raw data ingested directly from source systems (CSV files) into SQL Server without any transformation.
-Silver Layer:
Performs data cleaning, transformation, standardization, and normalization to make data analysis-ready.
-Gold Layer:
Contains business-ready data modeled using a star schema, optimized for reporting and analytics.

📖 Project Overview

This project includes:
-Data Architecture Design
Building a modern data warehouse using Bronze, Silver, and Gold layers.
-ETL Pipelines
Extracting, transforming, and loading data from ERP and CRM systems.
-Data Modeling
Creating fact and dimension tables for efficient analytical querying.
-Analytics & Reporting
Writing SQL queries to generate insights and business reports.

🎯 Key Skills Demonstrated

This project showcases expertise in:
-SQL Development
-Data Engineering
-ETL Pipeline Development
-Data Modeling (Star Schema)
-Data Analytics & Reporting

🛠️ Tools & Technologies
-SQL Server Express – Database engine
-SQL Server Management Studio (SSMS) – Database management
-Draw.io – Architecture & data modeling diagrams
-Notion – Project planning and documentation
-GitHub – Version control and collaboration

🚀 Project Requirements
📌 Data Engineering
Objective:
Build a data warehouse to consolidate sales data from multiple sources for analytical reporting.

Key Tasks:
-Import data from ERP and CRM systems (CSV files)
-Perform data cleaning and handle data quality issues
-Integrate data into a unified analytical model
-Focus on the latest dataset (no historization required)
-Document the data model clearly

📊 Data Analytics
Objective:
Generate insights using SQL queries on the warehouse data.

Key Insights:
-Customer behavior analysis
-Product performance tracking
-Sales trend analysis

📂 Repository Structure
data-warehouse-project/
│
├── datasets/                           # Raw data (ERP & CRM)
│
├── docs/                               # Documentation
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── naming-conventions.md
│
├── scripts/                            # SQL scripts
│   ├── bronze/                         # Raw data ingestion
│   ├── silver/                         # Data cleaning & transformation
│   ├── gold/                           # Analytical models
│
├── tests/                              # Data quality tests
│
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt

🛡️ License
This project is licensed under the MIT License. You are free to use, modify, and share it with proper attribution.

🌟 About Me
Hi! I'm Harshini, a Data Analyst with passion for data analytics.
I enjoy working on data-driven projects that transform raw data into meaningful insights and support business decision-making.
