# Azure Tutorial for Beginners - Comprehensive Notes

This README provides structured notes on the fundamental Azure concepts and services covered in the Azure tutorial video. It’s your go-to document if you’re entering the **Azure Data Engineering** space or looking to deepen your understanding.

---

Azure Tutorial by Ansh Lamba: 
https://youtu.be/S417kGaBerM?si=XHZepn4cgcsB1JQT

---


## 📌 Table of Contents
- [Introduction to Azure and Cloud Computing](#introduction-to-azure-and-cloud-computing)
- [Why Azure is in High Demand](#why-azure-is-in-high-demand)
- [Types of Cloud Services](#types-of-cloud-services)
  - [On-Premise vs Cloud](#on-premise-vs-cloud)
  - [IaaS](#iaas-infrastructure-as-a-service)
  - [PaaS](#paas-platform-as-a-service)
  - [SaaS](#saas-software-as-a-service)
- [Fault Tolerance & Data Redundancy](#fault-tolerance--data-redundancy)
  - [Availability Models](#availability-models)
  - [Redundancy Policies](#redundancy-policies)
- [Azure Portal Walkthrough](#azure-portal-walkthrough)
- [Core Data Services in Azure](#core-data-services-in-azure)
  - [Structured Data - Azure SQL Database](#structured-data---azure-sql-database)
  - [Semi-Structured Data - Azure Cosmos DB](#semi-structured-data---azure-cosmos-db)
  - [Unstructured Data - Azure Data Lake](#unstructured-data---azure-data-lake)
- [Real-Time Data Services](#real-time-data-services)
  - [Azure Event Hubs](#azure-event-hubs)
- [Data Processing Services](#data-processing-services)
  - [Azure Data Factory (ADF)](#azure-data-factory-adf)
  - [Azure Databricks](#azure-databricks)
  - [Azure Synapse Analytics](#azure-synapse-analytics)
- [Account Setup & Resource Groups](#account-setup--resource-groups)
- [Conclusion](#conclusion)

---

## Introduction to Azure and Cloud Computing

- **Cloud**: Centralized data storage accessible via the internet.
- Solves problems like accessibility, storage scalability, and cost.
- Cloud computing extends this by offering **on-demand computing resources**.

---

## Why Azure is in High Demand

- High market demand with limited skilled professionals.
- Growing adoption across enterprises for data infrastructure and DevOps.
- Great opportunity for aspiring data engineers and cloud professionals.

---

## Types of Cloud Services

### On-Premise vs Cloud

| Feature        | On-Premise                      | Cloud (Azure, AWS, GCP)             |
|----------------|----------------------------------|--------------------------------------|
| Setup          | Owned infrastructure            | Rented virtual infrastructure        |
| Maintenance    | Self-managed                    | Managed by Cloud Provider            |
| Scalability    | Hard                            | Very easy                            |

### IaaS (Infrastructure as a Service)
- Provides virtualized computing infrastructure.
- Example: **Azure Virtual Machines**
- You manage: OS, applications, data
- Azure manages: Physical server, networking

### PaaS (Platform as a Service)
- Provides platform and environment for development.
- Example: **Azure SQL Database**
- You focus on data & applications, Azure handles rest (OS, runtime, infrastructure).

### SaaS (Software as a Service)
- Full software solution delivered via cloud.
- Example: **Microsoft Fabric**
- You manage only your data and user settings.

---

## Fault Tolerance & Data Redundancy

### Availability Models
- **Availability Zones**: Independent physical locations within a region.
- **Region Pairs**: Replication between regions for disaster recovery.

### Redundancy Policies

| Policy | Copies | Location | Use Case |
|--------|--------|----------|----------|
| Locally Redundant Storage (LRS)  | 3      | Single Data Center | Cost-efficient |
| Zone-Redundant Storage (ZRS)    | 3      | Across Zones in Region | More reliable |
| Geo-Redundant Storage (GRS)    | 6 (3 + 3) | Across 2 Regions | High redundancy |
| Geo-Zone-Redundant Storage   | 6 (3+3 across zones & region) | Across Regions & Zones | Most reliable |

---

## Azure Portal Walkthrough

- URL: [https://portal.azure.com](https://portal.azure.com)
- Key Areas:
  - **Resource Groups** – Logical folders for organizing related Azure resources.
  - **All Resources** – Lists all active resources.
  - **Microsoft Entra ID** – Formerly Azure Active Directory for identity & access management.
  - **Cost Management** – Monitor Azure spend.

---

## Core Data Services in Azure

### Structured Data - Azure SQL Database
- Managed relational database.
- Good for tabular data (rows/columns).
- Supports SQL queries, ACID transactions.
- **Ideal for OLTP and relational apps**.

### Semi-Structured Data - Azure Cosmos DB
- Globally distributed NoSQL DB.
- Supports APIs: Core (SQL), MongoDB, Cassandra, Gremlin, Table.
- JSON-like storage (key-value).
- HTAP: Supports transactional and analytical queries.

### Unstructured Data - Azure Data Lake
- Stores blobs, files, logs, videos, images.
- Hierarchical storage structure.
- **Ideal for big data analytics and AI/ML workloads**.

---

## Real-Time Data Services

### Azure Event Hubs
- Ingest real-time events at high scale.
- Used in streaming pipelines, logs, telemetry.
- Works with Spark, Stream Analytics, Data Lake.

---

## Data Processing Services

### Azure Data Factory (ADF)
- Cloud ETL service.
- Drag-and-drop pipelines.
- Supports scheduled and trigger-based workflows.
- Connects with various on-prem/cloud data sources.

### Azure Databricks
- Apache Spark-based analytics platform.
- Supports real-time & batch data processing.
- Ideal for data scientists and machine learning workloads.

### Azure Synapse Analytics
- Unified analytics platform.
- Combines big data and data warehousing.
- Supports serverless and provisioned queries.

---

## Account Setup & Resource Groups

- **Free Trial**: [Azure Free Account](https://azure.microsoft.com/en-in/free/)
  - 200 USD credit for 30 days.
  - Limited free-tier services.
- **Resource Group**: Logical container for related services.
- **Subscription**: Billing unit for organizing resources per department/project.
- **Tenant**: Identity boundary within Azure (typically your organization/domain).

---

## Conclusion

By the end of this tutorial, you should be able to:
- Understand Azure cloud fundamentals.
- Set up your free Azure account.
- Use the Azure Portal confidently.
- Deploy and manage key data services: SQL DB, Cosmos DB, Data Lake, Event Hub, ADF, Synapse, Databricks.
- Understand pricing and fault tolerance options in Azure.

---

