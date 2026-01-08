# Batch Analytics ETL Pipeline

## Overview
This project demonstrates a batch-based data engineering pipeline designed to process raw datasets into analytics-ready formats. The pipeline uses Apache Airflow for orchestration, Apache Spark for data processing, and S3-compatible object storage for data lake implementation. The goal of this project is to understand batch ETL workflows and analytics engineering concepts.

This project is adapted from an open-source reference and customized for academic learning and practical experimentation.

---

## Architecture

Data Source (CSV / Public Dataset)
↓
Python & Spark Transformations
↓
Apache Airflow (Batch Orchestration)
↓
S3-Compatible Object Storage (MinIO)
↓
Analytics-Ready Tables & Reports

---

## Key Features
- Batch-based ETL data pipeline
- Workflow scheduling with Apache Airflow
- Data transformations using Apache Spark
- Object storage–based data lake design
- Containerized execution using Docker

---

## Technologies Used
- Python
- Apache Airflow
- Apache Spark
- DuckDB
- MinIO (S3 compatible storage)
- PostgreSQL
- Docker & Docker Compose

---

## Learning Objectives
- Understand batch ETL data pipeline design
- Learn orchestration using Apache Airflow
- Apply Spark transformations on structured data
- Explore data lake concepts using object storage
- Gain hands-on experience with analytics engineering workflows

---

## Getting Started

### Prerequisites
- Docker Desktop
- Docker Compose
- Git

### Run the Pipeline
```bash
make up
Access Airflow UI at:

arduino
Copy code
http://localhost:8080
Username and password: airflow

Project Scope
This project focuses on learning batch data engineering concepts, pipeline orchestration, and system integration. It is intended for educational and portfolio purposes rather than production deployment.

Disclaimer
This project is adapted from an open-source reference for educational use. The implementation and documentation have been modified to reflect personal learning and customization.