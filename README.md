# 📊 Real-Time Stock Market Insights Pipeline (MarketPulse)

## 📌 Project Overview

MarketPulse Analytics is a real-time data engineering pipeline that simulates a fintech-grade stock market analytics system.

It collects live stock market data from an external API, streams it through Kafka, processes it using Apache Spark, stores it in PostgreSQL, and visualizes insights using Power BI dashboards.

This project demonstrates a complete end-to-end **real-time data pipeline architecture** used in modern financial systems.

---

## 🏢 Business Context

MarketPulse Analytics provides real-time financial insights for institutional investors, hedge funds, and trading firms.

The system is designed to reduce data latency and enable faster decision-making in high-frequency trading environments.

---

## 🧱 Architecture

Stock Market API  
↓  
Apache Kafka (Streaming Layer)  
↓  
Apache Spark (ETL Processing)  
↓  
PostgreSQL (Storage Layer)  
↓  
Power BI (Visualization Layer)

---

## ⚙️ Tech Stack

- Python  
- Apache Kafka  
- Apache Spark (PySpark)  
- PostgreSQL  
- Power BI  
- Docker & Docker Compose  
- REST API (Alpha Vantage)

---

## 🔄 Data Pipeline Flow

1. **API Layer**
   - Fetches real-time stock market data

2. **Kafka Layer**
   - Streams data into `stock_data` topic

3. **Spark Layer**
   - Consumes streaming data
   - Cleans and transforms data (ETL process)

4. **PostgreSQL Layer**
   - Stores processed structured data

5. **Power BI Layer**
   - Visualizes data for business insights
