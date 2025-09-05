# sql-data-warehouse-project
Creating a Modern Data warehouse with SQL and ETL Process, data modelling and analystics 
📖 Overview

This project sets up a new Data Warehouse (DWH) in SQL Server to centralize data from multiple sources, enable advanced analytics, and support business intelligence (BI) reporting.

The solution is designed to provide:

A single source of truth for enterprise data.

ETL pipelines for extracting, transforming, and loading data.

Data models optimized for reporting and analytics.

Scalability for future integrations and advanced analytics (AI/ML).

🏗️ Project Architecture

Components include:

Source Systems – ERP, CRM, Marketing, and other operational systems.

Staging Layer – Temporary storage for raw ingested data.

Transformation Layer – Cleansing, standardization, and business logic application.

Data Warehouse Layer – Star/Snowflake schema with fact and dimension tables.

Data Marts – Subject-area specific views (Sales, Finance, HR, etc.).

BI Layer – Tools like Power BI / Tableau for dashboards and reports.

⚙️ Technology Stack

Database: Microsoft SQL Server (2019/2022).

ETL Tool: SQL Server Integration Services (SSIS) / Azure Data Factory (optional).

Version Control: GitHub / Azure DevOps.

Reporting: Power BI / SSRS.

🚀 Setup Instructions
1. Prerequisites

SQL Server installed (Developer/Enterprise edition recommended).

SQL Server Management Studio (SSMS).

Access to source systems/data files.

Git client (for version control).

2. Database Creation
CREATE DATABASE DataWarehouse;
GO

3. Schema Setup

Staging: stg schema for raw data.

Data Warehouse: dwh schema for cleaned and modeled data.

Data Mart: dm schema for subject-specific data marts.
