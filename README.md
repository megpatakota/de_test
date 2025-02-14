# Retail Analytics Data Pipeline

[![Project Status](https://img.shields.io/badge/Status-Active-green)]()
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)]()
[![Docker](https://img.shields.io/badge/Docker-Enabled-blue)]()

## 📌 Overview
This project builds a **Retail Analytics Data Pipeline** using **MongoDB, PostgreSQL, and Apache Spark** to support **data-driven decision-making** for a retail company. The pipeline handles data ingestion, transformation, and querying for insights.

## 🚀 Features
- **Data Ingestion**: Loads structured data into **MongoDB**.
- **ETL Process**: Transfers data from **MongoDB to PostgreSQL**.
- **Analytics**: Uses **Apache Spark** to analyze data.
- **Persistent Storage**: Ensures data is retained using **Docker volumes**.
- **Jupyter Notebook Support**: Runs the pipeline in a **Jupyter environment**.

## 📝 Notes
- Ensure **Docker is installed and running** before executing.
- Modify `main.py` for additional data processing steps.
- For persistence, always restart Jupyter using:
```bash
docker start -ai my_jupyter
```

---
🚀 Happy Coding! If you have any questions, feel free to reach out!

