# Data Engineering & Business Intelligence: Dimensional Modeling, ETL & Advanced Tableau

> Designed dimensional data warehouse models, implemented ETL pipelines in Talend, and built advanced Tableau dashboards to support enterprise reporting, analytics, and decision-making.

**Author:** Amisha Farhana Shaik  
**Project Type:** Data Engineering | Data Warehousing | ETL | Business Intelligence  

---

## Project Overview

This repository consolidates hands-on labs covering the full Data Engineering and Business Intelligence lifecycle:

- Dimensional modeling & star schema design  
- Slowly Changing Dimensions (SCD Types 1, 2, 3, 6)  
- Accumulating and periodic snapshot fact tables  
- ETL workflows using Talend  
- Data integration and transformation  
- Advanced Tableau dashboard development  
- Forecasting, clustering, ranking, and interactive analytics  

The goal was to design scalable analytical systems that support enterprise reporting and performance monitoring.

---

# 1️⃣ Dimensional Modeling & Star Schema Design

Designed dimensional models for multiple business scenarios including:

- E-wallet liability tracking  
- Global product distribution profitability  
- Used car dealership purchase & sale lifecycle  
- Retail transaction modeling  

## Key Concepts Implemented

- Business process identification  
- Fact table grain definition  
- Surrogate vs natural keys  
- Conformed dimensions  
- Composite fact keys  
- Profit and margin calculations  
- Accumulating fact tables  
- Periodic snapshot facts  

## Slowly Changing Dimensions (SCD)

Evaluated and implemented:

- **Type 1** – Overwrite (no history)
- **Type 2** – Historical tracking with effective & expiration dates
- **Type 3** – Limited history via new columns
- **Type 6** – Hybrid (1+2+3 for HR-style high-change environments)

Designed a Type 6 employee dimension with:
- Historical Job Title
- Current Job Title
- Start/End dates
- Current indicator flag

---

# 2️⃣ Data Warehouse Enhancements & Hierarchies

Implemented:

- Bridge tables for organizational hierarchy modeling
- Parent-child dimension structures
- Multi-level reporting hierarchies
- Hospital star schema enhancements
- Supertype/subtype dimension extensions

These designs support flexible reporting across evolving organizational structures.

---

# 3️⃣ ETL & Data Integration (Talend)

Built complete ETL workflows using Talend:

## Core Transformations

- File ingestion via metadata  
- Duplicate removal  
- Inner joins & reject flows  
- Aggregations (Total by Customer)  
- Conditional routing (High vs Low Charge split)  
- Sorting and filtering  
- File existence validation  
- Iterative file loading using `tFileList`  
- Logging and error handling  

## Outputs Generated

- Cleaned Excel exports  
- Aggregated customer metrics  
- Conditional high/low transaction reports  
- Joined customer-order datasets  
- Consolidated multi-file integrations  

This demonstrates practical ETL pipeline development and operational data preparation.

---

# 4️⃣ Advanced Tableau Business Intelligence

Developed interactive dashboards covering:

## Core Visualizations

- Bar charts & cross tables  
- Highlight tables & heat maps  
- Scatter plots (aggregated & disaggregated)  
- Dual-axis & combined-axis charts  
- Symbol maps  

## Advanced Analytics

- Running totals & percent-of-total  
- Ranking calculations  
- Profit margin calculations  
- String/date calculations  
- Trend lines & forecasting  
- Clustering analysis  

## Dashboard Engineering

- Filter actions  
- Highlight actions  
- Hyperlink actions  
- Navigation buttons  
- Context filters (Top N filtering)  
- Hierarchies  
- Groups & sets  
- Parameter-driven interactions  

These dashboards simulate enterprise BI reporting systems.

---

# End-to-End Architecture

Business Process
        ↓
Dimensional Modeling (Star Schema)
        ↓
ETL Pipelines (Talend)
        ↓
Data Warehouse Tables
        ↓
BI Layer (Tableau Dashboards)
        ↓
Executive Reporting & Decision Support

This mirrors real-world enterprise analytics architecture.

---

## Technical Skills Demonstrated

- Dimensional Modeling
- Star Schema Design
- Slowly Changing Dimensions (Type 1/2/3/6)
- Accumulating Fact Tables
- Bridge Tables & Hierarchies
- ETL Development (Talend)
- Data Cleansing & Aggregation
- SQL-style Analytical Thinking
- Tableau Advanced Analytics
- Dashboard Engineering & Interactivity
- Forecasting & Clustering
- Business KPI Modeling

---

## Why This Project Is Important

This project demonstrates:

- Full data lifecycle understanding  
- Data warehouse design thinking  
- Enterprise ETL implementation  
- BI dashboard engineering  
- Scalable reporting architecture  
- Historical tracking and governance  
- Performance & profitability analysis modeling  

It reflects real-world data engineering and BI workflows used in retail, finance, operations, and enterprise analytics teams.

---

## Applications

Data Engineering | Data Warehousing | Business Intelligence | ETL Development | Enterprise Reporting | Analytics Engineering
