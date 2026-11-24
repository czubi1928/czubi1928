<!-- 
Hi, I'm Patryk! This is the README for my GitHub profile.
I'm a PostgreSQL DBA / database engineer growing toward database reliability, cloud and data engineering roles.
This profile highlights my production database work and my data and cloud projects.
-->

# 👋 Hi, I'm Patryk Czubiński

## 👨‍💻 PostgreSQL Database Engineer & Administrator | Reliability, Performance & Migrations

I keep production data systems fast, reliable and recoverable. I started as a junior database developer, and today I look after a multi-tenant telematics SaaS platform with hundreds of GB of partitioned time-series data.

Outside work I build data pipelines and cloud projects (Airflow, dbt, Terraform, Snowflake), and I'm growing toward database reliability, cloud and data engineering roles.

📍 **Location:** Warsaw, Poland (open to remote work across the EU & UK)  
💬 **Languages:** English / Polski

---

## ⭐ Key Achievements

- Designed and deployed an **Apache Cassandra** data layer that increased write throughput by **428%** (6,014 → 31,748 records/sec) compared with the previous PostgreSQL setup
- Reclaimed **hundreds of GB of storage** by redesigning how historical partitions store semi-structured data and cleaning up **tens of thousands of unused partitions**
- Introduced a **safe-change standard** for production: per-task backups, transactional dry runs, rollback plans and result reports
- Built tested tooling for restoring historical data and moving vehicles with their full history between tenants (check → switch → copy → verify)
- Automated customer-data recovery in Python, cutting restore time **from hours to seconds**
- Led the rollout of **Prometheus + Grafana** monitoring and delivered dashboards as code (Python generator + validator that tests every query before deployment)
- Automated log analysis with **pgBadger**, cutting incident diagnosis time by **50%**; tuned autovacuum for **+10%** write speed
- Built a **FastAPI** microservice for GPS speed-limit lookups on OpenStreetMap data in PostgreSQL; a custom partial index brought responses down to milliseconds

## 🧩 Core Competencies

- **Database Engineering:** PostgreSQL (partitioning, schema design, migrations, performance tuning with pg_stat_statements, EXPLAIN ANALYZE, autovacuum and lock analysis), Apache Cassandra, Firebird, T-SQL
- **Reliability & Operations:** backup & DR (Barman, PITR, WAL archiving), replication monitoring, Prometheus, Grafana, safe production changes, Linux
- **Automation:** Python (Pandas, FastAPI, SQLAlchemy, pytest), SQL, Bash, Docker
- **Cloud & Data:** AWS, GCP, Terraform, Snowflake, Apache Airflow, dbt, DuckDB

---

## 🏗️ Featured Projects

### 1️⃣ [🪙 Bitcoin Monitor - Data Engineering Project](https://github.com/czubi1928/bitcoin_monitor) *(in progress)*

A Bitcoin price **monitoring tool** that **ingests** price data from the CoinCap API, **processes** and **models** it, and exposes **interactive dashboards** for trend analysis. The project demonstrates building a data pipeline with **infrastructure-as-code**, **orchestration** and **cloud data warehousing**.

**Tech Stack:** `Python` • `Pandas` • `Apache Airflow` • `dbt` • `Snowflake` • `Terraform` • `Docker` • `CoinCap API` • `Apache Superset`

**💡 Highlights:** ingestion and processing of Bitcoin prices, Airflow DAGs for orchestration, dbt models with tests and data quality monitoring (Elementary), Snowflake provisioned with Terraform as the analytics warehouse.

### 2️⃣ [🎵 Million Song - Data Engineering Project](https://github.com/czubi1928/million_song_project)

An **end-to-end data engineering project** built around the *Million Song Dataset*. It demonstrates a **modern data stack** for building scalable, testable, and automated data pipelines, from raw ingestion to analytics and visualization.

**Tech Stack:** `Python` • `Apache Airflow` • `dbt` • `DuckDB` • `PostgreSQL` • `MinIO (S3)` • `Apache Superset` • `Docker`

**💡 Highlights:** a complete data platform covering ingestion, transformation, dimensional modeling, orchestration, and visualization, with a focus on reliability and clean architecture.

### 3️⃣ [📋 IT Job Market Analysis](https://github.com/czubi1928/analyzing_job_offers)

A data analytics project that **scrapes, processes, and visualizes IT job advertisements** to uncover trends in skills demand, salary ranges, and role distributions.

**Tech Stack:** `Python` • `BeautifulSoup` • `Pandas` • `NumPy` • `SQL (SQLite)` • `Matplotlib` • `Seaborn` • `Jupyter`

**💡 Highlights:** turns raw, unstructured web data into a structured database and actionable insights.

### #️⃣ Other Noteworthy Projects

- **[Data Modeling With Postgres](https://github.com/czubi1928/data_modeling_with_postgres)** - Designed and implemented a star schema database for a music streaming startup
- **[Data Modeling With Cassandra](https://github.com/czubi1928/data_modeling_with_cassandra)** - Built a NoSQL data model on Apache Cassandra to handle high-throughput event data
- **[DE Airflow Tutorial](https://github.com/czubi1928/de_airflow_tutorial)** - A practical guide and project demonstrating core concepts of ETL orchestration with Airflow
- **[Data engineering project: data extraction to analysis](https://github.com/czubi1928/de_online_store)** - End-to-end project simulating extraction, transformation, loading, and analysis for an online store, with AWS infrastructure in Terraform
- **[Apache Superset Tutorial](https://github.com/czubi1928/superset_tutorial)** - A lightweight Docker-based setup for running Apache Superset

> See my repositories for READMEs, architecture diagrams, and runnable demos

---

## 🧰 Tech Stack & Tools

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Apache Cassandra](https://img.shields.io/badge/Apache%20Cassandra-1287B1?style=for-the-badge&logo=apache%20cassandra&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### Monitoring & Reliability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Data Processing & Orchestration

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Apache Superset](https://img.shields.io/badge/Apache%20Superset-01A1A1?style=for-the-badge&logo=apache%20superset&logoColor=white)

---

## 🎯 What I'm Working On Next

- ☁️ **Cloud databases:** PostgreSQL on AWS (RDS / Aurora) provisioned with Terraform
- 🛡️ **High availability:** streaming replication, Patroni and pgBackRest, with failover and restore drills
- ☸️ **Kubernetes:** running PostgreSQL with an operator (CloudNativePG)
- 🔄 **Streaming & CDC:** Kafka and Debezium on top of PostgreSQL
- 📘 **Certification:** an AWS Associate certification

---

## 🏅 Certifications & Credentials

- **[Astronomer Certification for Apache Airflow 3 Fundamentals](https://www.credly.com/badges/9d0a674d-5b7d-4fee-83bb-428977a9ef33/linked_in_profile)** - *Astronomer, 2025*
- **[DeepLearning.AI & AWS - Data Engineering](https://coursera.org/share/a7bfee985ac679659955f1c63be96c77)** - *DeepLearning.AI, 2025*
- **PostgreSQL Database Administration Fundamentals** - *JSystems*
- **Introduction to Data Engineering on Google Cloud** - *Compendium Centrum Edukacyjne, 2025*
- **Agentic AI** - *DeepLearning.AI, 2026*
- **[Prompt Design in Vertex AI Skill Badge](https://www.credly.com/badges/25d87922-1fe8-40d4-806d-0796f0ef0b86/linked_in_profile)** - *Google Cloud, 2024*

---

## 📫 Get in Touch

- **Email:** [czubi1928@gmail.com](mailto:czubi1928@gmail.com)
- **LinkedIn:** [linkedin.com/in/patryk-czubinski-1928-sql](https://linkedin.com/in/patryk-czubinski-1928-sql)
- **GitHub:** [github.com/czubi1928](https://github.com/czubi1928)
