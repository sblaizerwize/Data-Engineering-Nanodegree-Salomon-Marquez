# Data Engineering Nanodegree Portfolio

This repository contains four hands-on data engineering projects from the [data engineering nanodegree from Udacity](https://www.udacity.com/certificate/GJQ6XA9K) to implement data modeling, ETL, and analytics pipelines on Sparkify, a digital music application.

It demonstrates full data lifecycle from data ingestion, transformation, and storage design to validation, by implementing end-to-end ETL and analytics across NoSQL (`Cassandra`), relational (`PostgreSQL`), distributed processing (`Spark`), and cloud data warehousing (`Redshift`) architectures, enabling scalable music behavior analysis. 

## Content

| Folder | Focus | Learnings |
|---|---|---|
| `Data-Modeling-with-Cassandra` | Query-driven NoSQL design | Defined keyspaces and chose effective partition/clustering keys; structured tables around query patterns to enable fast key lookups with no joins. |
| `Data-Modeling-with-Postgres` | Star schema design + JSON ETL | Built Python ETL pipelines, enforced a proper star schema, and added checks to prevent duplicates and stale values while validating query outputs. |
| `Data-Modeling-with-Spark` | Spark-based ETL (local + EMR) | Worked with Spark DataFrames, wrote data to S3/parquet, and used partitioning to optimize reads and support scalable pipelines. |
| `Data-Modeling-with-Warehouses` | Redshift warehouse architecture | Designed resilient staging layers, supported incremental loads for analytic tables, and structured transformations with an emphasis on downstream analytical impact. |

## Getting started

1. Choose a project folder.  
2. Follow the step-by-step instructions in its README file.


