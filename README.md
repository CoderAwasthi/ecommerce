# E-commerce Lakehouse Pipeline

## Overview
A Databricks Lakehouse project built using the Bronze, Silver, and Gold architecture.

## Pipeline stages
- **Bronze:** Ingest source e-commerce CSV files into Delta tables.
- **Silver:** Clean, validate, and transform source data.
- **Gold:** Produce analytics-ready fact tables and daily sales metrics.
- **Data quality:** Validate key constraints and consistency.

## Orchestration
The `ecommerce_lakehouse_pipeline` Databricks Job orchestrates ingestion, transformations, analytics, and data-quality checks.

## Technology stack
- Databricks
- Apache Spark / PySpark
- Delta Lake
- Unity Catalog
- Git and GitHub

## Data source
The project uses the Olist Brazilian e-commerce dataset.

