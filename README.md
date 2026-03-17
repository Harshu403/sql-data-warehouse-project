# Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project 🚀
This project demonstrates an end-to-end data warehousing and analytics solution — from raw data ingestion to generating actionable business insights. It is designed as a portfolio project to showcase best practices in data engineering and data analytics.

## 🏗️ Data Architecture

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

## 📖 Project Overview

This project includes:
1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

## 🎯 Key Skills Demonstrated

**This project showcases expertise in:**
- SQL Development
- Data Engineering
- ETL Pipeline Development
- Data Modeling (Star Schema)
- Data Analytics & Reporting

## 🛠️ Tools & Technologies
- SQL Server Express – Database engine
- SQL Server Management Studio (SSMS) – Database management
- Draw.io – Architecture & data modeling diagrams
- Notion – Project planning and documentation
- GitHub – Version control and collaboration

## 🚀 Project Requirements
### 📌 Data Engineering
**Objective:**
Build a data warehouse to consolidate sales data from multiple sources for analytical reporting.

**Key Tasks:**
- Import data from ERP and CRM systems (CSV files)
- Perform data cleaning and handle data quality issues
- Integrate data into a unified analytical model
- Focus on the latest dataset (no historization required)
- Document the data model clearly

### 📊 Data Analytics
**Objective:**
Generate insights using SQL queries on the warehouse data.

**Key Insights:**
- Customer behavior analysis
- Product performance tracking
- Sales trend analysis

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
