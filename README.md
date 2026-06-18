# SentinelStream Security Analytics Platform

## Overview

SentinelStream is a real-time cybersecurity analytics platform designed to ingest, process, detect, and visualize security events at scale.

The platform simulates a modern Security Information and Event Management (SIEM) architecture using streaming technologies, cloud data engineering pipelines, and threat detection analytics.

The solution enables security teams to identify suspicious activities, investigate threats, and monitor enterprise environments through real-time intelligence.

---

## Business Problem

Modern organizations generate massive volumes of security logs from:

- Authentication Systems
- Network Devices
- Cloud Infrastructure
- Applications
- Endpoints

Traditional monitoring solutions often struggle with:

- High data volume
- Detection latency
- Alert fatigue
- Scalability limitations
- Fragmented security visibility

SentinelStream addresses these challenges using scalable streaming analytics and modern data engineering architectures.

---

## Team Members

- Sameer Ugale
- Siddhi Kale

---

## Architecture

### Data Ingestion

- Apache Kafka

### Stream Processing

- Apache Spark Structured Streaming

### Workflow Orchestration

- Apache Airflow

### Storage Layers

#### Bronze Layer

Raw Security Events

#### Silver Layer

Cleaned & Standardized Events

#### Gold Layer

Threat Intelligence & Detection Outputs

### Data Warehouse

- Snowflake

### Search & Investigation

- OpenSearch

### Visualization

- Streamlit
- Plotly

---

## Technologies Used

### Programming

- Python
- SQL

### Data Engineering

- Apache Kafka
- Apache Spark
- Apache Airflow
- Delta Lake
- Snowflake

### Analytics

- OpenSearch
- Streamlit
- Plotly

### Cloud Concepts

- Real-Time Streaming
- Data Lake Architecture
- ETL Pipelines
- Security Analytics

---

## Threat Detection Use Cases

### Brute Force Detection

Detect repeated failed login attempts.

### Impossible Travel Detection

Identify suspicious logins from geographically impossible locations.

### Port Scan Detection

Detect network reconnaissance activity.

### IP Reputation Monitoring

Flag known malicious IP addresses.

### Authentication Anomaly Detection

Identify unusual authentication patterns.

### Threat Intelligence Correlation

Combine multiple security indicators to improve detection accuracy.

---

## Data Pipeline Workflow

1. Security Event Generation
2. Kafka Data Ingestion
3. Spark Stream Processing
4. Data Validation & Enrichment
5. Bronze Layer Storage
6. Silver Layer Transformation
7. Gold Layer Detection Logic
8. Snowflake Warehousing
9. OpenSearch Indexing
10. Dashboard Visualization

---

## Key Features

- Real-Time Event Processing
- Threat Detection Engine
- Multi-Layer Data Architecture
- Security Dashboarding
- Incident Investigation Support
- Streaming Data Pipelines
- Security Intelligence Monitoring

---

## Analytics Dashboards

### Security Operations Dashboard

Tracks:

- Total Security Events
- Threat Alerts
- High-Risk Events
- Incident Trends

### Authentication Monitoring Dashboard

Tracks:

- Failed Logins
- Suspicious Logins
- User Activity

### Threat Intelligence Dashboard

Tracks:

- Malicious IP Activity
- Threat Categories
- Detection Frequency

### Network Security Dashboard

Tracks:

- Port Scans
- Network Events
- Security Incidents

---

## Business Impact

### Threat Visibility

Improved visibility into security events across systems.

### Faster Detection

Reduced detection latency through real-time processing.

### Centralized Monitoring

Provided unified security intelligence dashboards.

### Scalable Architecture

Designed for large-scale streaming security data.

### Security Operations Support

Enabled proactive threat investigation and monitoring.

---

## Future Enhancements

- Machine Learning Threat Detection
- User Behavior Analytics (UBA)
- Security Copilot Integration
- Generative AI Incident Summaries
- Cloud-Native Deployment
- Automated Incident Response

---

## Authors

Sameer Ugale
MS Data Science, University of the Pacific

Siddhi Kale
MS Data Science, University of the Pacific
