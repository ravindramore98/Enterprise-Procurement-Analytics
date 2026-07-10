# Enterprise Procurement Analytics Platform

## Overview

The Enterprise Procurement Analytics Platform is an end-to-end Azure Data Engineering project that simulates a real-world procurement analytics solution for a global manufacturing company.

The platform ingests procurement data from SAP ECC, processes it using Azure Data Factory and Azure Databricks, stores curated datasets in Delta Lake following the Medallion Architecture, and serves analytics through Azure Synapse and Power BI.

---

## Business Problem

Organizations generate procurement data from multiple ERP systems, making it difficult to:

- Track vendor performance
- Monitor procurement spending
- Detect duplicate purchase orders
- Analyze procurement cycle times
- Build a single source of truth for reporting

This project addresses these challenges by building a scalable cloud-based analytics platform.

---

## Technology Stack

- Azure Data Factory
- Azure Databricks
- PySpark
- Delta Lake
- Azure Data Lake Storage Gen2
- Azure SQL Database
- Azure Synapse Analytics
- Power BI
- Azure DevOps
- GitHub

---

## Architecture

SAP ECC
↓
Azure Data Factory
↓
Azure Data Lake Storage Gen2
↓
Bronze Layer
↓
Silver Layer
↓
Gold Layer
↓
Azure Synapse
↓
Power BI

---

## Project Status

🚧 Currently Under Development

Sprint 1 Completed
- Repository Created
- Project Structure Created
- Documentation Initialized

Upcoming Sprint
- Generate Enterprise Procurement Data
