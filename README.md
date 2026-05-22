# Databricks AutoLoader Demo

Cloud Storage Ingestion pipeline built on Databricks using Auto Loader.

## What this covers
- Batch and Streaming ingestion modes
- 4 real-world failure scenarios validated:
  1. Schema Evolution
  2. Duplicate Records
  3. Data Type Mismatch
  4. Late Arrivals

## Files
- `AutoLoaderDemo1` — Batch mode ingestion
- `AutoLoaderDemo2` — Streaming mode ingestion

## Tools & Technologies
- Databricks
- Apache Spark
- Auto Loader (cloudFiles)
- PySpark
- Delta Lake
