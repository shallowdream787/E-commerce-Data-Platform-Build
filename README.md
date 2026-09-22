# E-commerce-Data-Platform-Build
End-to-end AWS Data Lakehouse for e-commerce analytics, built with Glue, Spark, Iceberg, Redshift, and SageMaker. Processes 3M+ orders and supports BI analytics and real-time product recommendations.
Built an end-to-end **AWS Data Lakehouse** for e-commerce analytics using the **Medallion Architecture (Bronze/Silver/Gold)**, processing over **3 million order records**.

The Bronze layer uses **AWS Glue, Apache Spark, Amazon S3, and Apache Iceberg** to support incremental ingestion, schema evolution, and reliable ETL processing. The Silver layer performs data cleansing, deduplication, NULL handling, and multi-table joins to create reusable **fact and dimension tables**.

For the Gold layer, curated and pre-aggregated business metrics are loaded into **Amazon Redshift** to support high-performance BI analytics and reporting.

The project also includes a **collaborative filtering recommendation system** built from historical user purchase behavior. The model is trained and deployed with **Amazon SageMaker** and served through a real-time **SageMaker Endpoint API**.

**Tech Stack:** AWS Glue, Spark, S3, Apache Iceberg, Amazon Redshift, SageMaker, Python, SQL
