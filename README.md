# 🚀 FMCG Medallion Data Engineering Project
### End-to-End ETL Pipeline using Databricks & PySpark

## 📌 Project Overview
This project demonstrates an end-to-end data engineering pipeline built for an FMCG (Fast-Moving Consumer Goods) use case using the Medallion Architecture (Bronze → Silver → Gold).

The objective is to ingest raw data from cloud storage, apply structured transformations, ensure data quality, and deliver analytics-ready datasets for reporting and decision-making.

---

## 🧩 Business Problem
FMCG organizations deal with high-volume transactional, customer, and product data from multiple sources. Common challenges include:
- Inconsistent schemas and poor data quality
- Difficulty tracking KPIs across entities
- Lack of analytics-ready datasets
- Manual and time-consuming data reconciliation

This project addresses these issues by implementing a layered and scalable ETL architecture.

---

## 🛠️ Tech Stack
- **Cloud Storage:** AWS S3
- **Data Processing:** Databricks, PySpark
- **Data Format:** Delta Lake
- **Query Engine:** Databricks SQL
- **Architecture:** Medallion (Bronze, Silver, Gold)
- **Visualization (Downstream):** Power BI / Databricks SQL

---

## 🏗️ Architecture Overview
##      AWS S3 (Raw Data)
#                ↓
## Databricks Bronze Layer (Raw Ingestion)
#                ↓
## Databricks Silver Layer (Cleaned & Standardized)
#                ↓
## Databricks Gold Layer (Business Aggregates)
#                ↓
## Analytics & Dashboards (Power BI / Databricks SQL)



---

## 🥉 Bronze Layer – Raw Data
- Ingested raw FMCG datasets from AWS S3
- Stored data in Delta format
- Applied minimal transformations
- Preserved original schema for traceability

**Purpose:** Maintain raw data for auditing and replay.

---

## 🥈 Silver Layer – Cleaned Data
- Removed duplicates and invalid records
- Handled missing and inconsistent values
- Standardized schemas
- Prepared fact and dimension-ready datasets
- Applied data quality checks

**Purpose:** Provide clean, reliable, analytics-ready data.

---

## 🥇 Gold Layer – Business Data
- Built aggregated tables for KPIs and reporting
- Designed fact and dimension tables
- Optimized tables for fast analytical queries
- Enabled direct BI consumption

**Purpose:** Deliver business-level insights.

---

## 🔄 ETL Pipeline Highlights
- End-to-end ETL using PySpark
- Batch processing with scalable transformations
- Schema enforcement and validation
- Delta Lake optimizations
- Production-oriented pipeline design

---

## 📊 Analytical Use Cases
- Sales performance analysis
- Product-level revenue insights
- Regional and time-based trend analysis
- KPI monitoring for FMCG operations

---

## 📈 Key Outcomes
- Standardized raw data into analytics-ready datasets
- Improved data quality and consistency
- Reduced manual reconciliation effort
- Enabled faster reporting and insights

---

## 📷 Project Documentation
Due to platform-specific dependencies (Databricks and BI tools), dashboards and pipelines are not fully hosted in this repository.

However, the project is documented through walkthroughs, visuals, and explanations on my LinkedIn profile.

---

## 👩‍💻 Author
**Anjali Vishwari**  
Aspiring Data Engineer  

- LinkedIn: https://www.linkedin.com/in/anjalivishwari  
- GitHub: https://github.com/anjalivishwari1506  

---

## 📌 Note
This repository demonstrates data engineering concepts, architecture, and ETL design using sanitized or sample datasets to represent real-world production workflows.

