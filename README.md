# ✈️ Flight Booking Data Pipeline with Airflow & CI/CD

This project demonstrates an end-to-end **Flight Booking Data Pipeline** built using **PySpark**, **Google Cloud Platform (GCP)** services, **Apache Airflow (Composer)**, and **CI/CD automation** with **GitHub Actions**.

## 🚀 Project Overview

The goal of this project is to process and transform flight booking data into meaningful business insights using scalable and maintainable data engineering practices.

## 🧰 Tech Stack

- **Language & Frameworks**: Python, PySpark  
- **Orchestration**: Apache Airflow (GCP Composer)  
- **Data Processing**: GCP Dataproc Serverless  
- **Data Storage**: Google Cloud Storage (GCS), BigQuery  
- **CI/CD**: GitHub Actions  

## 🛠️ Key Features

- Ingest raw flight booking JSON data stored in **Google Cloud Storage**  
- Transform data using **PySpark** on **Dataproc Serverless**  
- Load the cleaned & enriched data into **BigQuery** tables  
- Schedule and monitor the pipeline using **Apache Airflow DAGs**  
- Enable automated deployment via **GitHub Actions CI/CD pipeline**


## 🧪 How It Works

1. **Trigger**: DAG is scheduled or triggered manually in Airflow (Composer).  
2. **Detection**: DAG checks for new flight booking files in **GCS**.  
3. **Processing**: PySpark job is executed on **Dataproc Serverless** to transform the data.  
4. **Loading**: The transformed data is written to **BigQuery**.  
5. **CI/CD**: GitHub Actions automatically deploy updated DAGs and scripts to **GCS**.
