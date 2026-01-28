# Batch Processing Data Pipeline

This repository contains a containerized batch-processing data architecture
for a retail analytics use case.

## Services
- Ingestion service: loads raw sales data into PostgreSQL
- Processing service: performs batch ETL and aggregation
- PostgreSQL database: stores raw and curated data

## How to run
1. Copy `.env.example` to `.env`
2. Run `docker-compose up --build`
