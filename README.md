🏎️ Formula One Race Data Analysis in Databricks
This project is a comprehensive end-to-end analytics solution built on Databricks, designed to explore and analyze Formula One (F1) race data from the inception year (1950) to the present. The goal is to deliver insights into races, drivers, teams, circuits, and seasonal performance trends using a modern data engineering stack.






📊 Project Overview
Formula One is one of the most data-rich and historically detailed sports. This project harnesses publicly available F1 data to:

Ingest raw race and driver data from multiple years

Clean, transform, and enrich the data using Spark

Perform exploratory and advanced analysis

Create reusable and scalable data pipelines

Visualize trends in driver and constructor performance over decades





🔧 Technologies Used
Databricks (Lakehouse Platform)

Apache Spark (PySpark)

Delta Lake for data storage and versioning

Databricks Notebooks for development and visualization

SQL and Python for data transformation and analysis

dbutils and widgets for parameterization

MLflow (optional) for tracking experiments or models






 Data Sources
Ergast Developer API

Historical race CSVs (manually downloaded or API-pulled)









🚀 How to Run
Clone the repository into your Databricks workspace

Upload the raw dataset (or configure API ingestion)

Run the notebooks in order:

01_data_ingestion.py

02_data_cleaning_transformation.py

etc.

Visualize key insights in dashboards

Use widgets to filter by year, driver, constructor, etc.
