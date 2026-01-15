# 🚀 Day 7 – Workflows & Job Orchestration  
**Databricks 14 Days AI Challenge**  

---

## 📌 Overview

Day 7 focused on **workflow automation and job orchestration** in Databricks. Moving beyond interactive notebooks, the session explored how to build **production-ready pipelines** with scheduling, parameters, dependencies, and error handling.

This is crucial for building **robust, scalable Lakehouse pipelines** that automate Bronze → Silver → Gold data processing.

---

## 📚 Learning Objectives

- Understand **Databricks Jobs vs Notebooks**  
- Build **multi-task workflows**  
- Pass **parameters and schedule executions**  
- Implement **error handling and retry logic**  

---

## 🛠️ Hands-on Tasks

1. Add **parameter widgets** to notebooks  
2. Create **multi-task job** for Bronze → Silver → Gold  
3. Set up **task dependencies** to enforce execution order  
4. Schedule **automated daily execution**  

---

## 🛠️ Create Multi-Task Job

The workflow is implemented using **Databricks Jobs** (via UI or API) with multiple dependent tasks to ensure correct execution order.

### Workflow Tasks

- **Task 1: Bronze Ingestion**  
  Ingest raw data into the Bronze layer.

- **Task 2: Silver Cleaning**  
  Clean, validate, and standardize data.  
  *Depends on Task 1.*

- **Task 3: Gold Aggregates**  
  Generate business-level aggregates.  
  *Depends on Task 2.*

---

## ⛓️ Task Dependencies & Scheduling

- Task dependencies ensure workflows run **sequentially**
- Jobs can be scheduled to run **daily or hourly**
- Retry policies can be configured to handle **transient failures**
- Failed tasks can trigger alerts for operational visibility

---

## 💡 Key Takeaways

- Jobs automate **notebook execution** and enable reproducible pipelines  
- Multi-task workflows enforce **sequential dependencies**  
- Parameter widgets make pipelines **dynamic and reusable**  
- Scheduling and error handling are essential for **production-ready data engineering**  
- Orchestration is a critical skill for maintaining **Lakehouse pipelines at scale**

---

## 🔗 Resources

- **Databricks Jobs Overview**  
  https://docs.databricks.com/jobs.html  

- **Workflow Orchestration Guide**  
  https://docs.databricks.com/jobs/workflows.html  

- **Scheduling & Parameters**  
  https://docs.databricks.com/jobs/tasks.html#parameters  

---

## 📈 Challenge Progress

- [x] Day 1 – Apache Spark Basics  
- [x] Day 2 – Spark Fundamentals  
- [x] Day 3 – PySpark Transformations  
- [x] Day 4 – Delta Lake Introduction  
- [x] Day 5 – Delta Lake Advanced  
- [x] Day 6 – Medallion Architecture  
- [x] Day 7 – Workflows & Job Orchestration  

---

## 🙌 Acknowledgements

Thanks to **Databricks**, **Codebasics**, and **Indian Data Club** for organizing and supporting this hands-on learning challenge.

---

⭐ If you find this repository helpful, consider **starring it** and following along for upcoming days.
