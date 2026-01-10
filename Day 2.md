# 🚀 Day 2 – Apache Spark Fundamentals  
## Databricks 14 Days AI Challenge

This repository documents my **Day 2 learning progress** as part of the **Databricks 14 Days AI Challenge**, organized by **Indian Data Club**, **Codebasics**, and **Databricks**.

---

## 📌 Objective
To understand the **core fundamentals of Apache Spark**, its execution model, and how Databricks simplifies large-scale data processing using Spark.

---

## 📖 Topics Covered

### 🔹 Apache Spark Architecture
- Driver
- Executors
- Cluster Manager
- Directed Acyclic Graph (DAG)

### 🔹 Core Concepts
- DataFrames vs RDDs
- Lazy Evaluation
- Transformations vs Actions
- Distributed processing model

### 🔹 Databricks Notebook Features
- `%python`
- `%sql`
- `%fs`
- Interactive execution & visualization

---

## 🛠️ Hands-on Tasks Completed

- Uploaded sample e-commerce CSV dataset
- Loaded data into Spark DataFrame
- Performed basic transformations and actions:
  - `select`
  - `filter`
  - `groupBy`
  - `orderBy`
- Explored aggregations and counts

---

## 🧪 Practice Code Snippets

### Load Dataset
```python
events = spark.read.csv(
    "/path/to/sample.csv",
    header=True,
    inferSchema=True
)
