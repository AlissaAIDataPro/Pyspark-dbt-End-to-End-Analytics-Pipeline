# PySpark & DBT Analytics Pipeline
**End-to-End Data Engineering Project | Medallion Architecture | Delta Lake | SCD Type 2**

[![Project Report](https://img.shields.io/badge/Report-View%20Details-blue)](link-to-report)

Production-grade analytics pipeline built on Databricks demonstrating modern data engineering practices:

* **Incremental ingestion** via PySpark Structured Streaming
* **Bronze → Silver → Gold** medallion architecture with Delta Lake
* **SCD Type 2** dimensional modeling using DBT snapshots
* **Modular Python classes** for reusable transformation logic
* **DBT Cloud orchestration** with Jinja templating
* **Complete BI layer** with analytics-ready views

## Tech Stack

**PySpark** • **DBT** • **Delta Lake** • **Databricks** • **Python** • **SQL** • **Jinja** • **Git** • **YAML**

## Key Features

✅ **Exactly-once processing** with checkpointing and idempotent operations  
✅ **Dynamic schema handling** with automated ingestion pipelines  
✅ **Advanced deduplication** using window functions and hashing  
✅ **Conditional upserts** with Delta Table merge operations  
✅ **Full historical tracking** via SCD Type 2 snapshots  
✅ **Production-ready patterns** for cost optimization and scalability  

## Dataset

Pseudo-Uber ride-sharing dataset including:
- **Trips** (ride details, timestamps, distances)
- **Customers** (rider profiles and preferences)
- **Drivers** (driver information and ratings)
- **Vehicles** (fleet details)
- **Payments** (transaction records)
- **Locations** (pickup/dropoff zones)

## Architecture Highlights

### Bronze Layer
Raw data ingestion from CSV files using PySpark Structured Streaming with automatic schema inference and checkpointing.

### Silver Layer
- Data cleaning with regex patterns and conditional logic
- Deduplication using window functions
- Delta merge operations for incremental upserts
- Audit columns for data governance

### Gold Layer
- DBT incremental models with Jinja templating
- Dimensional modeling (facts and dimensions)
- SCD Type 2 for slowly changing dimensions
- Analytics-ready views for BI consumption

## Skills Demonstrated

**Data Engineering:**
- Structured streaming and incremental processing
- Medallion architecture implementation
- ACID transactions with Delta Lake
- Idempotent pipeline design

**Development Practices:**
- Object-oriented Python for modular transformations
- Version control with Git
- DBT best practices (sources, tests, documentation)
- Dynamic SQL generation with Jinja

**Data Modeling:**
- Dimensional modeling (star schema)
- SCD Type 2 implementation
- Data quality and governance patterns
- Lineage tracking and documentation

## Platform

Built on **Databricks Community Edition** (free tier) with Unity Catalog, demonstrating cloud-agnostic patterns applicable to Azure, AWS, and GCP.

---

*This project showcases real-world data engineering skills with production-grade practices for scalable analytics pipelines.*
