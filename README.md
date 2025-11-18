# Pinecone_Airflow
This project runs a full Pinecone vector search pipeline using Apache Airflow on Docker. It includes installing sentence-transformers, configuring Pinecone, preprocessing data, creating an index, generating embeddings, ingesting them into Pinecone, and running a semantic search — with screenshots of each Airflow task.

### Pinecone + Airflow Pipeline (Docker Setup)

This repository contains a complete workflow for running a Pinecone vector search pipeline as an Apache Airflow DAG using Docker.
The project includes:

Modified docker-compose.yaml with sentence-transformers and pinecone-client

Pinecone API setup and Airflow Variable configuration

Data download, preprocessing, and input file generation

Pinecone index creation

Embedding generation and ingestion using sentence-transformers

Semantic search execution through Airflow tasks

All steps include screenshots of Airflow task logs and outputs.
This repo serves as a full demonstration of integrating vector databases with Airflow for data pipeline automation.
