# 🚀 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project Repository**!

This project demonstrates an end-to-end modern data warehousing and analytics solution — from raw data ingestion to generating actionable business insights. Designed as a portfolio project, it showcases practical implementation of data engineering, dimensional modeling, and SQL-based analytics using industry best practices.

---

# 🏗️ Architecture Overview – Medallion Architecture

This project follows the **Medallion Architecture** approach (Bronze → Silver → Gold layers).

## 🥉 Bronze Layer – Raw Data
- Stores raw data exactly as received from source systems.
- Data is ingested from CSV files into SQL Server.
- No transformations are applied.
- Ensures traceability and auditability.

## 🥈 Silver Layer – Cleaned & Transformed Data
- Data cleansing and standardization.
- Handling missing and null values.
- Removing duplicates.
- Data normalization.
- Preparing structured datasets for analysis.

## 🥇 Gold Layer – Business-Ready Data
- Data modeled into a **Star Schema**.
- Creation of Fact and Dimension tables.
- Optimized for analytical queries and reporting.
- Enables KPI tracking and business insights.

---

# 📖 Project Overview

This project includes:

## 🔹 Data Architecture
Designing a modern SQL-based data warehouse using Medallion Architecture.

## 🔹 ETL Pipelines
Extracting, transforming, and loading ERP and CRM data into the warehouse.

## 🔹 Data Modeling
Developing fact and dimension tables optimized for analytics.

## 🔹 Analytics & Reporting
Creating SQL-based reports to generate meaningful business insights.

---

# 🛠️ Tools & Technologies Used

- SQL Server Express – Database hosting
- SQL Server Management Studio (SSMS) – Database management
- Git & GitHub – Version control
- Draw.io – Architecture and data modeling diagrams
- Notion – Project tracking and documentation

---

# 📊 Project Requirements

## 🏗️ Building the Data Warehouse (Data Engineering)

### 🎯 Objective
Develop a SQL Server-based data warehouse to consolidate sales data for analytical reporting and informed decision-making.

### 📌 Specifications

**Data Sources:**
- ERP system (CSV files)
- CRM system (CSV files)

**Data Quality:**
- Cleanse and resolve inconsistencies
- Handle missing and duplicate records

**Integration:**
- Merge both sources into a unified analytical model

**Scope:**
- Focus on the latest dataset
- Historical tracking not required

**Documentation:**
- Provide clear data model documentation
- Ensure clarity for both business and analytics teams

---

## 📈 BI: Analytics & Reporting (Data Analysis)

### 🎯 Objective
Develop SQL-based analytics to generate insights on:

- Customer Behavior
- Product Performance
- Sales Trends

These insights support strategic decision-making and performance evaluation.

---

# 📂 Repository Structure

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




---

# 🛡️ License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this project with proper attribution.

---

# 🌟 About Me

Hi, I’m **Sakitha**, a Bachelor of Engineering (Computer Science) graduate exploring SQL and Data Engineering.

I am passionate about:
- Data Warehousing
- SQL Development
- Dimensional Modeling
- Analytics & Business Intelligence

This project represents my hands-on experience in designing and implementing a modern data warehouse using SQL Server.

I am continuously learning and expanding my expertise in data engineering and analytics.
