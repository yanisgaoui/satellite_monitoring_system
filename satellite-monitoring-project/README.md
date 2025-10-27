# Satellite and Space Objects Monitoring System

Système de monitoring en temps réel des satellites et objets spatiaux utilisant une architecture Lambda avec Apache Spark, Kafka, et Cassandra.

## Fonctionnalités

- Ingestion en temps réel des données TLE (Two-Line Elements)
- Calcul des positions satellites en temps réel
- Détection de risques de collision
- Analyse de patterns orbitaux
- Dashboard de visualisation 3D
- Prédiction de trajectoires

## Architecture

- **Ingestion**: Apache Kafka
- **Processing**: Apache Spark (Batch + Streaming)
- **Storage**: HDFS + Cassandra + Redis
- **Orchestration**: Kubernetes
- **API**: FastAPI
- **Monitoring**: Prometheus + Grafana

## Installation

Voir [INSTALLATION.md](INSTALLATION.md)

## Utilisation

Voir [USAGE.md](USAGE.md)
