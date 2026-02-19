# Batch Processing Data Pipeline for Retail Demand Forecasting

## Overview

This project implements a batch-processing data pipeline designed to support retail demand forecasting. The system demonstrates how raw retail transaction data can be ingested, stored, and processed using a modular microservices architecture.

The pipeline consists of three main components:

- PostgreSQL database – central persistent storage
- Ingestion service – loads raw retail data into the database
- Processing service – performs batch ETL and aggregation

All components are containerized and orchestrated using Docker Compose to ensure reproducibility and clear service integration.

---

## Architecture

The system follows a batch-processing architecture:

1. Raw retail data is ingested by the ingestion service.
2. Data is stored in the PostgreSQL database.
3. The processing service reads data from the database and performs batch transformations.
4. Processed data becomes available for analytics or machine learning use cases.

This modular design reflects real-world data engineering practices, emphasizing reproducibility, maintainability, and separation of concerns.

---

## Repository Structure

git clone https://github.com/Juliekith/data-engineering-batch-pipeline.git
