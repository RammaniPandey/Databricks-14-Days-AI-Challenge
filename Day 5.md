# 🚀 Day 5 – Delta Lake Advanced  
**Databricks 14 Days AI Challenge**  

---

## 📌 Overview

Day 5 dives into **advanced Delta Lake features** that are essential for maintaining, optimizing, and governing production-grade data pipelines. The focus is on version control, incremental updates, performance optimization, and storage cleanup.

These capabilities make Delta Lake a powerful backbone for scalable **Lakehouse Architecture** implementations.

---

## 📚 Learning Objectives

- Understand **Time Travel** and Delta table version history  
- Implement **MERGE operations** for incremental upserts  
- Optimize Delta tables using **OPTIMIZE & Z-ORDER**  
- Manage storage efficiently with **VACUUM**  

---

## 🧠 Key Concepts

### 🔹 Time Travel
Allows querying historical versions of a Delta table for auditing, debugging, and reproducibility.

### 🔹 MERGE (Upserts)
Efficiently handles inserts and updates in a single transactional operation.

### 🔹 OPTIMIZE & Z-ORDER
Improves query performance by compacting small files and clustering data based on access patterns.

### 🔹 VACUUM
Removes obsolete data files that are no longer referenced by the Delta transaction log.

---

## 🛠️ Hands-on Tasks

1. Implement **incremental MERGE** logic  
2. Query **historical versions** of Delta tables  
3. Optimize tables using **OPTIMIZE & ZORDER**  
4. Clean up old files using **VACUUM**  

---

## 💡 Key Takeaways

- Time travel enables **data auditing and rollback**
- **MERGE** simplifies incremental data ingestion
- **OPTIMIZE** and **Z-ORDER** significantly improve query performance
- **VACUUM** helps manage storage and maintain table hygiene
- Delta Lake is built for **production-scale data engineering**

---

## 🔗 Resources

- **Delta Lake Documentation**  
  https://docs.delta.io/latest/index.html  

- **Delta Lake Time Travel**  
  https://docs.delta.io/latest/delta-batch.html#query-an-older-snapshot-of-a-table  

- **Databricks Optimization Guide**  
  https://docs.databricks.com/delta/optimizations/index.html  

---

## 📈 Challenge Progress

- [x] Day 1 – Apache Spark Basics  
- [x] Day 2 – Spark Fundamentals  
- [x] Day 3 – PySpark Transformations  
- [x] Day 4 – Delta Lake Introduction  
- [x] Day 5 – Delta Lake Advanced  

---

## 🙌 Acknowledgements

Thanks to **Databricks**, **Codebasics**, and **Indian Data Club** for organizing and supporting this hands-on learning challenge.

---

⭐ If you find this repository helpful, consider **starring it** and following along for upcoming days.

