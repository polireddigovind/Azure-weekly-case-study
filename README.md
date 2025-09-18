# Azure Data Pipeline for Sales Analytics

This project implements an **end-to-end Azure cloud data pipeline** for processing large-scale sales data.  
The pipeline is built using **Azure Data Lake Storage (ADLS)**, **Azure Data Factory (ADF)**, **Databricks (PySpark)**, and follows the **Medallion Architecture**.  
The final curated data is connected to **Power BI** for building interactive sales dashboards.

---

## 🚀 Architecture

1. **Data Ingestion**  
   - Raw sales data ingested into **ADLS (Bronze layer)** using ADF.  

2. **Data Processing**  
   - **Databricks with PySpark** used for cleaning, transformation, and enrichment.  
   - Processed data stored in **ADLS Silver layer**.  

3. **Data Curation**  
   - Optimized and business-ready datasets written to **ADLS Gold layer**.  

4. **Visualization**  
   - Gold layer connected to **Power BI**, enabling sales performance dashboards and insights.  

---

## 🛠️ Tech Stack

- **Azure Data Lake Storage (ADLS)** – scalable cloud storage  
- **Azure Data Factory (ADF)** – orchestration & scheduling  
- **Azure Databricks (PySpark)** – transformation & processing  
- **GitHub** – version control & CI/CD integration  
- **Power BI** – data visualization & reporting  

---
