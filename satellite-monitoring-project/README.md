# Satellite and Space Objects Monitoring System

A real-time monitoring platform for satellites and space debris, built with a **Lambda Architecture** using **Apache Spark**, **Kafka**, and **Cassandra**.

## Features

* Real-time ingestion of **TLE (Two-Line Element)** data
* Real-time computation of satellite positions
* **Collision risk detection** and alert notifications
* **Orbital pattern analysis** and anomaly detection
* Interactive **3D visualization dashboard**
* **Trajectory prediction** using both historical and live data

## System Architecture

| Layer             | Technologies                     |
| ----------------- | -------------------------------- |
| **Ingestion**     | Apache Kafka                     |
| **Processing**    | Apache Spark (Batch + Streaming) |
| **Storage**       | HDFS · Cassandra · Redis         |
| **Orchestration** | Kubernetes                       |
| **API**           | FastAPI                          |
| **Monitoring**    | Prometheus · Grafana             |

## Installation

See the [INSTALLATION.md](INSTALLATION.md) file for detailed setup instructions.

## 🛰️ Usage

Refer to [USAGE.md](USAGE.md) for usage examples and workflow details.
