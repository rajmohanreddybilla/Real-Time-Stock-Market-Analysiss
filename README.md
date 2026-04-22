# 📊 Real-Time Stock Market Insights Pipeline (MarketPulse)

## 📌 Project Overview
MarketPulse Analytics is a real-time financial data pipeline designed to collect, process, and prepare stock market data for analytics and visualization.

The system fetches live stock data from an external API, processes it using a modular Python architecture, and runs inside a Docker container to ensure consistency across environments.

This project is the foundation for a scalable fintech-grade streaming pipeline that can later integrate Kafka, Spark, PostgreSQL, and Power BI for real-time analytics.

---

## 🏢 Company Context
MarketPulse Analytics is a fintech-focused data platform that provides real-time insights for institutional investors, hedge funds, and trading firms.  
This project simulates a simplified version of their real-time data infrastructure.

---

## 🧱 Architecture

Current Flow:

Stock Market API → Python Application → Docker Container

Planned Scalable Architecture:

Stock Market API → Kafka → Spark Streaming → PostgreSQL → Power BI Dashboard

---

## ⚙️ Tech Stack

- Python
- REST API (Alpha Vantage)
- Docker & Docker Compose
- dotenv (environment management)
- Git & GitHub (version control)

---

## 🚀 Features

- Real-time stock market data retrieval
- Modular Python code structure
- Secure API key management using `.env`
- Containerized application using Docker
- Scalable architecture ready for Kafka & Spark integration

---

## 📁 Project Structure
