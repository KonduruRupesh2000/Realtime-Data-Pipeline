# Realtime-Data-Pipeline

## Project Overview
Developed an end-to-end data pipeline for real-time data processing and analytics using modern data engineering tools. The system efficiently captures user data from API, processes it in real-time, and enables scalable data storage and analysis.

## Technology Stack
- **Apache Airflow**: Task orchestration and workflow automation
- **Apache Kafka**: Real-time data streaming and processing 
- **Apache Cassandra**: Scalable NoSQL database for processed data
- **PostgreSQL**: Metadata management for workflows
- **Docker**: Service containerization and deployment

## Pipeline Architecture
1. **Data Ingestion**: 
  - Simulated user data generation using Random User Generator API
  - Automated data fetching via Airflow DAGs
  - Real-time streaming through Kafka

2. **Processing & Storage**:
  - Data transformation using Apache Spark
  - Structured storage in Cassandra for efficient querying
  - Real-time monitoring with Kafka Control Center

## Implementation Highlights
- Created automated workflows using Airflow DAGs
- Built scalable data streaming pipeline with Kafka
- Implemented efficient data storage in Cassandra
- Containerized entire pipeline using Docker
- Set up real-time monitoring and visualization

## Key Outcomes
- Successfully built production-ready data pipeline
- Demonstrated end-to-end data engineering lifecycle
- Enabled real-time data processing capabilities
- Achieved scalable and efficient data storage
