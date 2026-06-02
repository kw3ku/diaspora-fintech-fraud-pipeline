# diaspora-fintech-fraud-pipeline

An enterprise-grade, end-to-end fraud detection and compliance data pipeline designed for high-throughput cross-border diaspora remittance platforms. Built using Microsoft Fabric, PySpark, SynapseML (LightGBM), and Delta Lake.

## 📌 Project Overview
Cross-border remittance platforms serving the global diaspora process millions of dollars in international transfers daily. These networks are prime targets for structured fraud schemes, structuring velocity anomalies, and geographic compliance bypasses. 

This project implements a fully automated, production-ready **Medallion Architecture** to ingest high-velocity semi-structured transaction logs, engineer behavioral risk features, and deploy a distributed machine learning model using **SynapseML** to flag high-risk transactions before financial clearing.

## 🏗️ Architecture & Data Engineering Design
The system decouples data processing stages into a transactional Delta Lake store to ensure ACID compliance, horizontal scalability, and low-latency feature extraction.

