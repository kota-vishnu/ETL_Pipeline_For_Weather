ETLWeather: Automated Weather Data Pipeline with Apache Airflow

**Overview**

ETLWeather is an automated ETL (Extract, Transform, Load) pipeline built using Apache Airflow and PostgreSQL to fetch, process, and store weather data. The pipeline extracts weather data from Open-Meteo API, transforms it, and loads it into a PostgreSQL database for further analysis.

This project showcases my ability to design and deploy scalable data pipelines, implement orchestrated workflows, and work with cloud-based ETL solutions.

**Key Features**

Automated ETL: Runs on a scheduled basis (@daily) using Apache Airflow.

Weather Data Extraction: Fetches real-time weather data from Open-Meteo API.

Data Storage: Loads processed data into a PostgreSQL database.

Dockerized Deployment: Uses Docker & Docker Compose for environment consistency.

Modular Airflow DAG: Implements best practices with Airflow decorators & Hooks.

Error Handling & Logging: Ensures robust pipeline execution.

**Tech Stack**

Apache Airflow (Task Orchestration)

PostgreSQL (Data Storage)

Docker & Docker Compose (Containerization)

Python (ETL & Data Processing)

HTTP API Integration (Open-Meteo API)

**How It Works**

Extract: The pipeline calls the Open-Meteo API using Airflow's HTTP Hook.

Transform: Parses JSON response, formats data, and prepares it for database insertion.

Load: Stores the structured data into a PostgreSQL database. 

**Insights from This Project**

Implemented modular DAG design for clean & scalable Airflow workflows.

Applied Airflow Hooks (HttpHook, PostgresHook) to simplify API calls and database interactions.

Utilized Dockerization for seamless deployment across different environments.

Gained experience in data pipeline orchestration, scheduling, and error handling.
