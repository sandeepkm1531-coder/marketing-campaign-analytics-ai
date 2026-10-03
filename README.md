# marketing-campaign-analytics-ai
Marketing campaign analytics using AWS S3 and Databricks, with planned ML and RAG extensions.
# Marketing Campaign Analytics and AI

A portfolio project using a 200,000-row marketing campaign dataset
to build a data pipeline, analytics dashboard, and planned ML
and RAG capabilities.

## Current progress

- Uploaded the source CSV to AWS S3.
- Configured Databricks Unity Catalog access using an IAM role,
  storage credential, and a marketing external location.
- Built and validated a Bronze Delta table.
- Preserved all 16 source columns as strings.
- Added source file, ingestion batch ID, and ingestion timestamp.
- Verified 200,000 rows and 19 columns.
- Used snapshot overwrite to prevent duplicate ingestion on reruns.

## Technology used

AWS S3, AWS IAM, Databricks, Unity Catalog, PySpark, and Delta Lake.

## Planned work

- Silver: data types, date parsing, and data quality checks.
- Gold: campaign performance and time-based reporting.
- Dashboard: marketing performance analysis.
- ML: prediction experiments with leakage checks and baseline evaluation.
- RAG: answers grounded in project documentation.
- Agent workflow: controlled access to analytics and prediction tools.

## Dataset

Marketing Campaign Performance dataset from Kaggle:
https://www.kaggle.com/datasets/manishabhatt22/marketing-campaign-performance-dataset

The source CSV is not included in this repository.
Dataset provenance, date meaning, and metric definitions will
be checked before interpreting trends or building models.

## Project status

Portfolio project in development. Bronze ingestion is complete.
This project has not been deployed to production.
