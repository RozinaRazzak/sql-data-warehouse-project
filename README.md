# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository!
THis project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights.Designed as a portfolio project highlights industry best practices in data enigineering and anlaytics.

# Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
![HLA](https://github.com/user-attachments/assets/fe68c350-ba54-46c8-becd-7e5676857b90)

### 1. Bronze Layer:
Stores raw dara as-is from the source systems. Data is ingested from CSV files into SQL Server Database.
### 2. Silver Layer:
This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
### 3. Gold Layer:
Houses business-ready data modeled into a star schema required for reporting and analytics.


# Project Overview

This project involves:

1. **Data Architecture:** Designing a Modern Data Warehouse using Medallion Architecture Bronze, Silver, and Gold layers.
2. **ETL Pipelines:** Extracting, transforming , and loading data from source systems into the warehouse.
3. **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.

This repository is an excellent resource for professionals and students looking to showcase expertise in :
* SQL Development
* Data Architect
* Data Engineering
* ETL Pipeline Developer
* Data Modeling
* Data Analytics

# Important Links & Tools:
Everything is free!
* **[Datasets](link of datasets in git hub):** Access to the project dataset(csv files).
* **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL databases.
* **[SQL Server Management Studio(SSMS)](https://learn.microsoft.com/en-us/ssms/install/install?view=sql-server-ver16):** GUI for managing and interacting with databases.
* **[Git Repository]():** Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
* **[DrawIO](https://www.drawio.com/)** Design data architecture, ,models, flows and diagrams.
* **[Notion Projects Steps](https://www.notion.so/Data-Warehouse-Project-22a27ebd508c8084897bc9473d0f3a33):** Access to all Project Phases and Tasks.
  
# Project Requirements
## Building the Data Warehouse (Data Engineering)
### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decison-making.

### Specifications
* **Data Sources:** Import data from two source systems(ERP and CRM) provided as CSV files.
* **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
* **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
* **Scope:** Focus on the latest dataset only; historization of data is not required.
* **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

# BI: Analytics & Reporting (Data Analysis)
### Objective:
Develop SQL-based analytics to deliver detailed insights  into:
* **Customer Behavior**
* **Product Performance**
* **Sales Trends**

These insights empower stakeholders with key businesss metrics, enabling stragetic decison-making.

# License
This project is licensed under the [MIT License](https://github.com/RozinaRazzak/sql-data-warehouse-project/blob/main/LICENSE). You are free to use, modeify and share this project with proper attribution.
