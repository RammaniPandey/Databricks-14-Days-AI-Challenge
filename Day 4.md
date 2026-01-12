# 🚀 Day 4 – Delta Lake Introduction  
**Databricks 14 Days AI Challenge**   

---

## 📌 Overview

Day 4 focuses on **Delta Lake**, a storage layer that brings reliability, consistency, and performance to data lakes. The session combines conceptual understanding with hands-on practice using **Databricks**, **Spark SQL**, and **PySpark**.

Delta Lake is a key component of the **Lakehouse Architecture**, enabling production-grade data engineering workflows.

---

## 📚 Learning Objectives

- Understand what **Delta Lake** is and why it is used  
- Learn about **ACID transactions** in data lakes  
- Explore **schema enforcement**  
- Compare **Delta Lake vs Parquet**  
- Create and manage **Delta tables** using SQL and PySpark  

---

## 🧠 Key Concepts

### 🔹 What is Delta Lake?
Delta Lake is an open-source storage layer built on top of Parquet that provides:
- ACID transactions  
- Schema enforcement & evolution  
- Time travel (data versioning)  
- Reliable batch and streaming data processing  

---

### 🔹 Delta Lake vs Parquet

| Feature | Parquet | Delta Lake |
|------|--------|-----------|
| File Format | Columnar | Columnar + Transaction Log |
| ACID Transactions | ❌ | ✅ |
| Schema Enforcement | ❌ | ✅ |
| Time Travel | ❌ | ✅ |
| Updates & Deletes | ❌ | ✅ |
| Reliability | Medium | High |

---

## 🛠️ Hands-on Tasks

1. Convert CSV files to **Delta format**  
2. Create Delta tables using:
   - Spark SQL  
   - PySpark  
3. Test **schema enforcement**  
4. Handle **duplicate inserts**  
5. Validate data consistency  

---

## 💡 Key Takeaways

- Delta Lake enables **ACID transactions** on data lakes  
- **Schema enforcement** prevents bad or inconsistent data ingestion  
- **MERGE operations** help manage duplicates effectively  
- Delta tables are ideal for **production-grade data pipelines**  
- Core building block of the **Lakehouse Architecture**

---

## 🔗 Resources

- **Delta Lake Documentation**  
  https://docs.delta.io/latest/index.html  

- **Delta Lake Quickstart Guide**  
  https://docs.delta.io/latest/quick-start.html  

- **Databricks Delta Lake Overview**  
  https://www.databricks.com/product/delta-lake  

---

## 🙌 Acknowledgements

Thanks to **Databricks**, **Codebasics**, and **Indian Data Club** for organizing and supporting this structured learning challenge.

---

⭐ If you find this repository helpful, consider **starring it** and following for upcoming days on GitHub.
