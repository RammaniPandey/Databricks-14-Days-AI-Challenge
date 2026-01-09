## Day 1 – Platform Setup & First Steps  
📅 Date: 09/01/2026

### 📌 Objective
Understand Databricks fundamentals and complete the initial platform setup.

---

### 📘 What I Learned
- Why **Databricks** is preferred over traditional **Pandas** and **Hadoop**
- High-level overview of **Lakehouse Architecture**
- Databricks workspace components:
  - Notebooks
  - Compute (Clusters)
  - Data Explorer
- Real-world adoption of Databricks in companies like Netflix and Shell

---

### 🛠️ Hands-on Tasks Completed
- Created **Databricks Community Edition** account
- Explored Workspace, Compute, and Data tabs
- Generated **Kaggle API credentials**
- Connected Kaggle with Databricks
- Downloaded and loaded an e-commerce dataset
- Executed first **PySpark DataFrame operations**

---

### 🧪 Practice Code
```python
# Create a simple DataFrame
data = [("iPhone", 999), ("Samsung", 799), ("MacBook", 1299)]
df = spark.createDataFrame(data, ["product", "price"])
df.show()

# Filter expensive products
df.filter(df.price > 1000).show()
