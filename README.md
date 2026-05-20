# Data Warehouse and Analytics Project 🚀

> **My first end-to-end data engineering project** — I'm incredibly excited to share this with the world! This project taught me so much about how data flows from raw sources all the way to business-ready insights.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** with three layers:

- **Bronze Layer** — Raw data ingested as-is from CSV source files into a SQL Server Database. No transformations, just pure storage.
- **Silver Layer** — Data cleansing, standardization, and normalization to make the data analysis-ready.
- **Gold Layer** — Business-ready data modeled into a **star schema**, optimized for reporting and analytics.

---

## 📖 Project Overview

This was my first attempt at building something real and end-to-end in data engineering. Here's what the project covers:

- **Data Architecture** — Designing a Modern Data Warehouse using Medallion Architecture (Bronze → Silver → Gold).
- **ETL Pipelines** — Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling** — Building fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting** — Writing SQL-based reports to surface actionable business insights.

This project gave me hands-on experience in areas I'm passionate about:

- SQL Development
- Data Architecture
- Data Engineering
- ETL Pipeline Development
- Data Modeling
- Data Analytics

---

## 🛠️ Tools & Resources Used

Everything used in this project is **free and open source**:

- **SQL Server Express** — Lightweight server for hosting the SQL database
- **SQL Server Management Studio (SSMS)** — GUI for managing and querying the database
- **DrawIO** — For designing architecture diagrams, data flow, and models
- **Git & GitHub** — Version control and project collaboration
- **Notion** — Project planning and task tracking

---

## 🚀 Project Requirements

### Building the Data Warehouse *(Data Engineering)*

**Objective:** Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications:**
- **Data Sources** — Two source systems (ERP and CRM) provided as CSV files
- **Data Quality** — Cleanse and resolve data quality issues before analysis
- **Integration** — Combine both sources into a single, unified data model designed for analytical queries
- **Scope** — Focus on the latest dataset only; historization is not required
- **Documentation** — Clear documentation of the data model for both business stakeholders and analytics teams

### Analytics & Reporting *(Data Analysis)*

**Objective:** Develop SQL-based analytics to deliver insights into:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics for strategic decision-making.

> See `docs/requirements.md` for full details.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture
│   ├── etl.drawio                      # ETL techniques and methods diagram
│   ├── data_architecture.drawio        # Overall project architecture
│   ├── data_catalog.md                 # Dataset catalog with field descriptions
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Star schema data models
│   └── naming-conventions.md          # Naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Raw data extraction and loading
│   ├── silver/                         # Data cleaning and transformation
│   └── gold/                           # Analytical model creation
│
├── tests/                              # Test scripts and quality checks
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information
├── .gitignore                          # Files excluded from version control
└── requirements.txt                    # Project dependencies
```

---

## 🌟 About Me

Hi! I'm **Omkar Khaladkar**, a data enthusiast just getting started on my journey in data engineering and analytics. This is my **first portfolio project**, and I built it to apply the concepts I've been learning and to demonstrate my interest in working with data at scale.

I'm actively developing my skills in SQL, data warehousing, and ETL development — and I'm excited to keep building and sharing more projects like this one. If you have any feedback or want to connect, I'd love to hear from you!

---

## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and share it with proper attribution.
