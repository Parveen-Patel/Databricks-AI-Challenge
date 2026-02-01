# Databricks-AI-Challenge
This documents my progress and projects from the 14-Day Databricks AI Challenge organized by Codebasics and Indian Data Club. It serves as both a learning log and a portfolio of hands-on work with Databricks, PySpark, and big data concepts.

# Day 1 (09/01/26) of the 14-Day Databricks AI Challenge
Today I took my first steps into the world of **Databricks** with **Codebasics** and the **Indian Data Club**, and it already feels like a whole new way of looking at data! 

---

## What I Did:
- Signed up for **Databricks Community Edition**
- Explored **Workspace, Compute, and Data Explorer**
- Created my very first **notebook**
- Ran my first few **PySpark commands** 

---

## Key Takeaways:
- Databricks makes working with **huge datasets** feel possible  
- Understanding the **workspace and compute setup** is just as important as writing code  
- Running PySpark for the first time was both **fun and rewarding**  

---

 # DAY 2 (10/01/26) – Apache Spark Fundamentals
Day 2 focused on understanding **Apache Spark basics** and performing fundamental data processing tasks using Spark.

---

## Concepts Learned:
- Spark architecture (driver, executors, DAG)
- DataFrames vs RDDs
- Lazy evaluation
- Notebook magic commands (`%sql`, `%python`, `%fs`)

## Outcome:
By the end of Day 2, I:
- Understood how Spark processes data internally
- Practiced working with Spark DataFrames
- Performed real-world style transformations
- Exported processed data for downstream use

# DAY 3 (11/01/26) – PySpark Transformations Deep Dive  
Day 3 focused on advanced **PySpark transformations**, joins, window functions, and feature engineering techniques used in real-world data pipelines.

---

## Concepts Learned:
- PySpark vs Pandas comparison
- Joins (inner, left, right, outer)
- Window functions (running totals, rankings)
- User-Defined Functions (UDFs)

## Outcome:
By the end of Day 3, I:
- Understood when to use PySpark over Pandas
- Applied multi-table joins to build enriched datasets
- Used window functions for advanced analytics
- Built derived features for downstream ML and reporting

# DAY 4 (12/01/26) – Delta Lake Introduction
Day 4 focused on understanding **Delta Lake** and how it brings reliability, performance, and data governance to data lakes.

---

## Concepts Learned:
- What is Delta Lake?
- ACID transactions
- Schema enforcement
- Delta vs Parquet

## Outcome:
By the end of Day 4, I:
- Understood how Delta Lake improves data lake reliability
- Worked with ACID-compliant tables
- Practiced schema enforcement and validation
- Managed duplicate data before writing to Delta

# PHASE 2: DATA ENGINEERING (Days 5–8)

## DAY 5 (13/01/26) – Delta Lake Advanced
---

## Concepts Learned:
- Time travel (version history)
- MERGE operations (upserts)
- OPTIMIZE & ZORDER
- VACUUM for cleanup

## Outcome:
By the end of Day 5, I:
- Implemented incremental data loads using MERGE
- Queried historical data versions using Delta Time Travel
- Improved performance using OPTIMIZE and ZORDER
- Cleaned up unused files with VACUUM

# 🚀 DAY 6 (14/01/26) – Medallion Architecture  
Day 6 focused on implementing the **Medallion Architecture** — a best-practice design pattern for building reliable and scalable data pipelines.

---

## Concepts Learned:
- Bronze (raw) → Silver (cleaned) → Gold (aggregated)
- Best practices for each layer
- Incremental processing patterns

## Outcome:
By the end of Day 6, I:
- Designed a Medallion (Bronze–Silver–Gold) architecture
- Built a raw ingestion layer
- Cleaned and validated data in the Silver layer
- Created business-ready aggregates in the Gold layer
This structure makes data pipelines more scalable, reliable, and analytics-ready.


# DAY 7 (15/01/26) – Workflows & Job Orchestration
Day 7 focused on automating data pipelines using **Databricks Workflows & Jobs**, turning notebooks into scheduled, reliable production processes.

---

## Concepts Learned:
- Databricks Jobs vs notebooks
- Multi-task workflows
- Parameters & scheduling
- Error handling

## Outcome:
By the end of Day 7, I:
- Converted notebooks into automated workflows
- Built a multi-stage data pipeline
- Passed parameters dynamically using widgets
- Scheduled reliable daily execution
This step bridges the gap between data engineering development and real production systems.


# DAY 8 (16/01/26) – Unity Catalog Governance
Day 8 focused on **Unity Catalog**, which provides centralized data governance, access control, and lineage across the Lakehouse.

---

## Concepts Learned:
- Catalog → Schema → Table hierarchy
- Access control (GRANT/REVOKE)
- Data lineage
- Managed vs external tables

## Outcome:
By the end of Day 8, I:
- Structured data using Catalog → Schema → Tables
- Applied role-based access control
- Understood data lineage tracking
- Differentiated between managed and external tables
- Created secure views for controlled data sharing
This step ensures the Lakehouse is not just powerful, but also secure, governed, and enterprise-ready.

# PHASE 3: ADVANCED ANALYTICS (Days 9–11)

## DAY 9 (17/01/26) – SQL Analytics & Dashboards
Day 9 focused on using **Databricks SQL** to run analytical queries and build interactive dashboards for business insights.

---

## Concepts Learned:
- SQL warehouses
- Complex analytical queries
- Dashboard creation
- Visualizations & filters

## Outcome:
By the end of Day 9, I:
- Used a SQL Warehouse for analytical workloads
- Wrote complex SQL queries to generate insights
- Built an interactive business dashboard
- Enabled filters and automated refresh for real-time reporting
This step turns data into decision-making insights.

# DAY 10 (18/01/26) – Performance Optimization
Day 10 focused on improving query and pipeline performance using optimization techniques in Databricks and Delta Lake.

---

## Concepts Learned:
- Query execution plans
- Partitioning strategies
- OPTIMIZE & ZORDER
- Caching techniques

## Outcome:
By the end of Day 10, I:
- Understood how to read query execution plans
- Applied partitioning for large datasets
- Used OPTIMIZE and ZORDER to improve data layout
- Benchmarked performance improvements
This step ensures pipelines are not just functional, but efficient and scalable.

# DAY 11 (19/01/26) – Statistical Analysis & ML Prep
Day 11 focused on using statistical techniques to understand data patterns and prepare features for machine learning models.

---

## Concepts Learned:
- Descriptive statistics
- Hypothesis testing
- A/B test design
- Feature engineering

## Outcome:
By the end of Day 11, I:
- Used descriptive statistics to understand data distribution
- Applied hypothesis testing concepts to compare groups
- Identified correlations between key variables
- Engineered new features to prepare for ML models
This step builds the bridge between data analysis and machine learning.

# PHASE 4: AI & ML (Days 12–14)

## DAY 12 (20/01/26) – MLflow Basics
Day 12 focused on **MLflow**, an open-source platform for managing the end-to-end machine learning lifecycle.

---

## Concepts Learned:
- MLflow components (tracking, registry, models)
- Experiment tracking
- Model logging
- MLflow UI

## Outcome:
By the end of Day 12, I:
- Understood the MLflow lifecycle
- Logged experiments with parameters and metrics
- Stored trained models as artifacts
- Compared multiple runs using the MLflow UI
This step brings structure and reproducibility to ML experimentation.

# 🚀 DAY 13 (21/01/26) – Model Comparison & Feature Engineering
Day 13 focused on training multiple machine learning models, performing feature engineering, and using Spark ML pipelines for scalable workflows.

---

## Concepts Learned:
- Training multiple models
- Hyperparameter tuning
- Feature importance
- Spark ML Pipelines

## Outcome:
By the end of Day 13, I:
- Trained and compared multiple ML models
- Used feature importance to understand key predictors
- Built reusable Spark ML pipelines
- Identified the best-performing model for prediction
This step bridges experimentation with scalable, production-ready ML.

# DAY 14 (22/01/26) – AI-Powered Analytics: Genie & Mosaic AI
Day 14 focused on exploring **AI-powered analytics**, leveraging **Databricks Genie** and **Mosaic AI** to generate insights and assist data analysis.

---

## Concepts Learned:
- Databricks Genie (natural language → SQL)
- Mosaic AI capabilities
- Generative AI integration
- AI-assisted analysis

## Outcome:
By the end of Day 14, I:
- Leveraged Genie for natural language querying
- Explored Mosaic AI for generative and predictive analytics
- Built a simple AI-powered NLP task
- Created actionable AI-assisted business insights
This final step demonstrates the full Lakehouse + AI workflow, transforming raw data into intelligent, actionable analytics.


