# TFM_unir

Main repository integrating the Python and Java developments of the real-time anomaly detection Master's thesis. It contains two independent submodules:

- [TFM_python](./TFM_python): Python development with Airflow, Dataflow, Dataproc, and Docker for data ingestion, processing, and model training.
- [TFM_java](./TFM_java): Java development for Flink, packaged as a JAR for real-time inference from Kafka.

## Abstract

Anomaly detection is a critical task across multiple sectors such as finance, the Internet of Things (IoT), and cybersecurity, where identifying unusual events in real time is essential to prevent fraud, system failures, or infrastructure attacks. Currently, handling large volumes of data, commonly referred to as Big Data, requires the use of scalable and efficient processing tools such as the distributed execution engines Apache Spark and Apache Flink. These tools support both batch and streaming processing, enabling real-time responsiveness. At the same time, machine learning models—ranging from simpler approaches such as logistic regression to more sophisticated architectures like autoencoders—provide an effective means of detecting anomalous patterns in complex, high-dimensional datasets.

This master's thesis focuses on the design and implementation of an anomaly detection system that integrates tools such as Apache Spark and Apache Flink, leveraging Google Cloud Platform (GCP). The aim is to combine distributed processing capabilities, both batch and streaming, to address the training and inference phases using artificial intelligence models.

**Keywords:** Apache Spark, Apache Flink, Cloud, Anomaly Detection, Batch, Streaming, Distributed Processing

## Description

The project combines distributed processing and machine learning to detect anomalies in real time across finance, IoT, and cybersecurity. Spark is used for batch training, and Flink for streaming inference.

## Technologies

- Apache Spark (Dataproc)
- Apache Flink
- Google Cloud Platform (Dataflow, Storage)
- Docker (Debezium, PostgreSQL)
- Kafka (streaming)
- Python & Java

## Cloning with submodules

```bash
git clone --recurse-submodules https://github.com/jaalcol/TFM_unir.git
git submodule update --remote --merge
```



# Spanish Version

## Resumen

La detección de anomalías es una tarea crítica en múltiples sectores como las finanzas, el Internet de las cosas (IoT) y la ciberseguridad, entre otros, donde la identificación de eventos inusuales en tiempo real resulta esencial para prevenir fraudes, fallos del sistema o ataques a la infraestructura. En la actualidad, el manejo de grandes volúmenes de datos, conocido comúnmente como Big Data, requiere el uso herramientas escalables y eficientes de procesamiento como son los motores de ejecución de procesamiento distribuido Apache Spark y Apache Flink. Estas herramientas permiten tanto procesamiento por lotes como en flujo, lo que facilita una repuesta en tiempo real. Por otra parte, el uso de modelos de machine learning —ya sea mediante enfoques más simples como la regresión logística o arquitecturas más sofisticadas como autoencoders— ofrecen una estrategia eficaz para la detección de patrones anómalos en conjuntos de datos complejos y de alta dimensionalidad.

Esta tesis de máster se centra en el diseño y la implementación de un sistema de detección de anomalías integrando herramientas como Apache Spark y Apache Flink, y empleando la plataforma de servicios en la nube de Google conocido como Google Cloud Platform (GCP). El objetivo es combinar capacidades de procesamiento distribuido, tanto en batch como en streaming, para abordar las fases de entrenamiento e inferencia mediante el uso de modelos de inteligencia artificial.

**Palabras clave:** Apache Spark, Apache Flink, Cloud, Detección de Anomalías, Batch, Streaming, Procesamiento Distribuido