# 🚕 Synapse NYC Taxi Analytics Project

## 📌 Overview
The **Synapse NYC Taxi Analytics Project** is an end-to-end, production-grade data engineering and analytics solution built using **Azure Synapse Analytics**.  
It processes large-scale **NYC Taxi trip data** to generate analytical insights on trip behavior, fare patterns, zones, and passenger trends using a **medallion architecture (Bronze → Silver → Gold)**.

This project demonstrates real-world enterprise data engineering practices including orchestration, transformation, analytics, and BI integration.

---

## 🏗️ Architecture
The solution follows a **modern cloud data architecture**:

- **Data Ingestion**: Raw NYC Taxi data ingested into Synapse  
- **Processing Engine**: Apache Spark (Synapse Spark Pools)  
- **Storage Layers**:
  - **Bronze** – Raw ingested data  
  - **Silver** – Cleaned and standardized data  
  - **Gold** – Aggregated, analytics-ready datasets  
- **Orchestration**: Synapse Pipelines & Triggers  
- **Analytics & BI**: SQL Scripts & Power BI integration  

---

## 📂 Repository Structure
```text
.
├── credential/               # Credentials configuration
├── dataset/                  # Dataset definitions
├── integrationRuntime/       # Integration runtime setup
├── linkedService/            # Linked services (Synapse, Power BI, Storage)
├── notebook/                 # Spark notebooks (Bronze, Silver, Gold)
├── pipeline/                 # Synapse pipelines for orchestration
├── sqlscript/                # SQL scripts for analytics & aggregations
├── trigger/                  # Pipeline triggers (scheduled/event-based)
├── publish_config.json       # Synapse publish configuration
└── README.md                 # Project documentation
```

## 🔄 Data Processing Flow

### Ingestion (Bronze Layer)
- Raw NYC Taxi trip data loaded using Spark notebooks  
- Minimal transformations applied  

### Transformation (Silver Layer)
- Data cleansing and validation  
- Schema standardization  
- Zone and trip enrichment  

### Aggregation (Gold Layer)
- Business-level aggregations  
- Trip, fare, passenger, and zone analytics  
- Optimized tables for reporting  

---

## ⚙️ Key Components

### 🔹 Synapse Notebooks
- Spark-based transformations  
- Scalable processing for large datasets  
- Modular Bronze, Silver, and Gold notebooks  

### 🔹 Synapse Pipelines
- End-to-end workflow orchestration  
- Parameterized pipelines  
- Central execution pipeline for full refresh  

### 🔹 SQL Scripts
- Analytical queries on Gold layer  
- Optimized for reporting and BI consumption  

### 🔹 Triggers
- Automated pipeline execution  
- Supports scheduled data refresh  

### 🔹 Power BI Integration
- Linked Service for Power BI  
- Gold datasets exposed for dashboards and reporting  

---

## 📊 Use Cases & Insights
- Trip volume trends by date and zone  
- Fare distribution analysis  
- Passenger count behavior  
- Popular pickup and drop-off zones  
- Time-based demand patterns  

---

## 🔐 Production-Grade Features
- Modular and reusable pipelines  
- Layered data architecture  
- Scalable Spark processing  
- Separation of concerns (ingestion, transformation, analytics)  
- Enterprise-ready Synapse deployment structure  

---

## 🚀 Technologies Used
- Azure Synapse Analytics  
- Apache Spark  
- Azure Data Lake / Storage  
- Azure Synapse Pipelines  
- SQL  
- Power BI  

---

## 🧠 Learning Outcomes
- Building enterprise-grade data pipelines  
- Implementing medallion architecture  
- Working with Synapse Spark & SQL pools  
- Orchestrating workflows using Synapse Pipelines  
- Preparing analytics-ready datasets for BI  

---

## 📎 Project Status
✅ Completed  
📈 Ready for analytics and BI consumption  
🛠️ Designed with production standards in mind  

---

## 👤 Author
**Manish Kumar Rai**  
Data Engineer | Azure Synapse | Big Data Analytics

