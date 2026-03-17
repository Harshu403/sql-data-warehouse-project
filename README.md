# Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project 🚀
This project demonstrates an end-to-end data warehousing and analytics solution — from raw data ingestion to generating actionable business insights. It is designed as a portfolio project to showcase best practices in data engineering and data analytics.

## 🏗️ Data Architecture

This project follows the Medallion Architecture approach:
-Bronze Layer:
Stores raw data ingested directly from source systems (CSV files) into SQL Server without any transformation.
-Silver Layer:
Performs data cleaning, transformation, standardization, and normalization to make data analysis-ready.
-Gold Layer:
Contains business-ready data modeled using a star schema, optimized for reporting and analytics.

## 📖 Project Overview

This project includes:
-Data Architecture Design
Building a modern data warehouse using Bronze, Silver, and Gold layers.
-ETL Pipelines
Extracting, transforming, and loading data from ERP and CRM systems.
-Data Modeling
Creating fact and dimension tables for efficient analytical querying.
-Analytics & Reporting
Writing SQL queries to generate insights and business reports.

## 🎯 Key Skills Demonstrated

This project showcases expertise in:
-SQL Development
-Data Engineering
-ETL Pipeline Development
-Data Modeling (Star Schema)
-Data Analytics & Reporting

## 🛠️ Tools & Technologies
-SQL Server Express – Database engine
-SQL Server Management Studio (SSMS) – Database management
-Draw.io – Architecture & data modeling diagrams
-Notion – Project planning and documentation
-GitHub – Version control and collaboration

## 🚀 Project Requirements
### 📌 Data Engineering
Objective:
Build a data warehouse to consolidate sales data from multiple sources for analytical reporting.

Key Tasks:
-Import data from ERP and CRM systems (CSV files)
-Perform data cleaning and handle data quality issues
-Integrate data into a unified analytical model
-Focus on the latest dataset (no historization required)
-Document the data model clearly

### 📊 Data Analytics
Objective:
Generate insights using SQL queries on the warehouse data.

Key Insights:
-Customer behavior analysis
-Product performance tracking
-Sales trend analysis

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---

## 🛡️ License
This project is licensed under the MIT License. You are free to use, modify, and share it with proper attribution.

## 🌟 About Me
Hi! I'm Harshini, a Data Analyst with passion for data analytics.
I enjoy working on data-driven projects that transform raw data into meaningful insights and support business decision-making.
