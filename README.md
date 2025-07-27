# Retailer Sales ETL

## Overview
This Airflow DAG automates the ingestion and transformation of retailer sales data. It performs the following steps:

Creates the required BigQuery dataset and tables if they do not exist.

Loads JSON data files from GCS buckets into staging tables.

Performs an UPSERT (SCD Type 1) merge into a target BigQuery table, updating existing rows or inserting new ones.

This approach ensures the data warehouse contains the latest and most accurate retailer sales information.

## Features
This Airflow DAG automates the ingestion and transformation of retailer sales data. It performs the following steps:

* Creates the required BigQuery dataset and tables if they do not exist.

* Loads JSON data files from GCS buckets into staging tables.

* Performs an UPSERT (SCD Type 1) merge into a target BigQuery table, updating existing rows or inserting new ones.

This approach ensures the data warehouse contains the latest and most accurate retailer sales information.

## Technologies
* Apache Airflow

* Google Cloud Platform

  * Google Cloud Storage (GCS)

  * BigQuery

* Python
