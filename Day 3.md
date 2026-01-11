# 📅 Day 3 – PySpark Transformations Deep Dive

## 📌 Overview
Day 3 focuses on **advanced PySpark transformations** used in real-world big data pipelines. The emphasis is on understanding how PySpark scales compared to Pandas, performing complex joins, leveraging window functions for analytical computations, and creating derived features using built-in functions and UDFs.

This day is designed to strengthen practical data engineering and analytics skills using distributed data processing.

---

## 🎯 Learning Objectives

By the end of Day 3, you will be able to:

- Understand **PySpark vs Pandas** differences and use cases
- Perform **SQL-style joins** in PySpark
- Apply **window functions** for running totals and rankings
- Create **derived features** for analytics and ML pipelines
- Work efficiently with large e-commerce datasets

---

## 🧠 Concepts Covered

### 🔹 PySpark vs Pandas
| Feature | Pandas | PySpark |
|------|------|------|
| Data Size | Small to Medium | Very Large (Distributed) |
| Execution | Single Machine | Cluster-based |
| Speed | Slower for big data | Optimized for scale |
| Use Case | Data analysis | Big data processing |

---

### 🔹 Joins in PySpark
- Inner Join
- Left Join
- Right Join
- Outer Join  

Used to combine multiple datasets such as users, products, and events.

---

### 🔹 Window Functions
Used for:
- Running totals
- Ranking
- Cumulative metrics
- Time-based analytics

---

### 🔹 User-Defined Functions (UDFs)
Custom logic applied to Spark DataFrames when built-in functions are insufficient.

---

## 🛠️ Tasks Completed

1. Loaded full e-commerce event dataset
2. Performed complex joins across datasets
3. Calculated running totals using window functions
4. Created derived analytical features

---

## 🧪 Practice Code

```python
from pyspark.sql import functions as F
from pyspark.sql.window import Window

# Top 5 products by revenue
revenue = events.filter(F.col("event_type") == "purchase") \
    .groupBy("product_id", "product_name") \
    .agg(F.sum("price").alias("revenue")) \
    .orderBy(F.desc("revenue")) \
    .limit(5)

revenue.show()
