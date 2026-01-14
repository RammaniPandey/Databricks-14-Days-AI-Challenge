# 🚀 Day 6 – Medallion Architecture  
**Databricks 14 Days AI Challenge**  

---

## 📌 Overview

Day 6 focuses on the **Medallion Architecture**, a widely adopted design pattern in modern data platforms and lakehouse implementations. This architecture organizes data into three logical layers — **Bronze, Silver, and Gold** — enabling scalable, maintainable, and high-quality data pipelines.

The session combined **architecture design principles** with **hands-on implementation** using PySpark and Delta Lake.

---

## 📚 Learning Objectives

- Understand the **Bronze → Silver → Gold** data flow  
- Learn best practices for each medallion layer  
- Apply **incremental processing patterns**  
- Build analytics-ready datasets using Delta Lake  

---

## 🧠 Medallion Architecture Layers

### 🥉 Bronze Layer (Raw Data)
- Stores raw ingested data
- Minimal transformations
- Preserves source fidelity
- Enables reprocessing if needed

### 🥈 Silver Layer (Cleaned & Enriched)
- Data cleaning and validation
- Deduplication
- Standardization and enrichment
- Business-rule enforcement

### 🥇 Gold Layer (Business Aggregates)
- Aggregated, analytics-ready datasets
- Optimized for reporting and BI
- Serves downstream analytics and ML use cases

---

## 🛠️ Hands-on Tasks

1. Designed a **3-layer Medallion Architecture**
2. Built **Bronze layer** for raw ingestion
3. Built **Silver layer** with cleaning and validation
4. Built **Gold layer** with business-level aggregations

---
    
## 💡 Key Takeaways

- Medallion Architecture enforces **clear data separation**
- Bronze layer ensures **data traceability and reprocessing**
- Silver layer improves **data quality and consistency**
- Gold layer delivers **business-ready insights**
- Incremental processing improves **efficiency and scalability**
- Foundational pattern for **enterprise Lakehouse systems**

---

## 🔗 Resources

- **Medallion Architecture (Databricks)**  
  https://www.databricks.com/glossary/medallion-architecture  

- **Architecture Explanation Video**  
  https://www.youtube.com/watch?v=njjBdmAQnR0  

- **Build a Medallion Architecture with Databricks**  
  https://youtu.be/yy9H4mlOG6I  

- **Incremental Processing Patterns**  
  https://youtu.be/GjV2m8b9fNY  

---

## 📈 Challenge Progress

- [x] Day 1 – Apache Spark Basics  
- [x] Day 2 – Spark Fundamentals  
- [x] Day 3 – PySpark Transformations  
- [x] Day 4 – Delta Lake Introduction  
- [x] Day 5 – Delta Lake Advanced  
- [x] Day 6 – Medallion Architecture  

---

## 🙌 Acknowledgements

Thanks to **Databricks**, **Codebasics**, and **Indian Data Club** for organizing and supporting this structured learning challenge.

---

⭐ If you find this repository helpful, consider **starring it** and following along for upcoming days.

