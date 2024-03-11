# Data Flow and Pipelines

Explore Google Cloud's managed services for data flows and pipelines.

## Overview

GCP offers several kinds of data flow and pipline services.

## Included Cloud Services

- **Pub/Sub**: Scalable and reliable messaging service for asynchronous communication between applications and services.
  - **Tech Stack**:  Apache Kafka
  
- **Dataflow**: Fully managed service for real-time and batch data processing using Apache Beam.
  - **Tech Stack**:  Apache Beam
  
- **Dataproc**: Fully managed Apache Spark and Hadoop service for big data processing.
  - **Tech Stack**:  Apache Spark, Apache Hadoop
  
- **Workflow**: Workflow orchestration service for coordinating and managing complex tasks and dependencies.
  - **Tech Stack**:  Apache Airflow, Kubernetes
  
- **Data Fusion**: Fully managed, code-free data integration service for building and managing data pipelines.
  - **Tech Stack**:  Apache Nifi, Apache Kafka
  
- **Composer**: Managed workflow orchestration service based on Apache Airflow for authoring, scheduling, and monitoring workflows.
  - **Tech Stack**:  Apache Airflow

## Comparision Tech Stack

**Apache Airflow**:

- **Purpose**: Orchestrate workflows using Directed Acyclic Graphs (DAGs).
- **Features**: Task scheduling, dependency management, monitoring.
- **Tech Stack**: Python-based, supports various databases.

**Apache Beam**:

- **Purpose**: Unified programming model for data processing pipelines.
- **Features**: Batch and stream processing, windowing, stateful processing.
- **Tech Stack**: Primarily Java-based, supports multiple languages and execution engines.

**Apache Nifi**:

- **Purpose**: Data ingestion, routing, transformation, and delivery.
- **Features**: Visual flow-based programming, data provenance, real-time processing.
- **Tech Stack**: Java-based, web-based UI, supports various data sources and sinks.


## Usage

Explore examples and resources to jumpstart your projects.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
