# Apache Pinot (apache-pinot)
Apache Pinot is a real-time distributed OLAP datastore designed to deliver scalable real-time analytics with low latency. It ingests data from batch and streaming sources and provides fast analytical queries for user-facing applications.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-pinot/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-pinot/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Database, Low Latency, OLAP, Real-Time, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Pinot REST API
The Pinot API provides REST endpoints for SQL queries, schema management, table management, segment management, cluster administration, and task management, along with a JDBC driver for SQL access.

**Human URL:** [https://docs.pinot.apache.org/](https://docs.pinot.apache.org/)

#### Tags:

 - Analytics, OLAP, REST, SQL, Apache, Open Source

#### Properties

- [Documentation](https://docs.pinot.apache.org/)
- [OpenAPI](openapi/apache-pinot-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/pinot)
- [Documentation](https://docs.pinot.apache.org/)
- [SpectralRules](rules/apache-pinot-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-pinot-vocabulary.yaml)
- [NaftikoCapability](capabilities/pinot-workflow.yaml)
- [JSON-LD](json-ld/apache-pinot-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Real-Time OLAP | Sub-second analytical queries over real-time and historical data |
| SQL Support | Standard SQL query interface with Pinot-specific extensions |
| Streaming Ingestion | Real-time data ingestion from Kafka, Kinesis, and Pulsar |
| Batch Ingestion | Offline data ingestion from HDFS, S3, GCS, and local files |
| Columnar Storage | Column-oriented storage with bitmap indexing for fast queries |
| Multi-Tenancy | Tenant isolation for broker and server resources |
| Star-Tree Index | Pre-aggregated star-tree index for metric rollup queries |

## Use Cases

| Name | Description |
|------|-------------|
| User-Facing Analytics | Power user-facing dashboards like LinkedIn Who Viewed Profile |
| Real-Time Dashboards | Business intelligence dashboards over streaming data |
| Anomaly Detection | Real-time anomaly detection over metric time series |
| A/B Testing | Real-time experiment analysis and statistical significance |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Real-time stream ingestion from Kafka topics |
| Apache Flink | Flink connector for streaming data into Pinot |
| Apache Superset | Visual analytics and dashboards via SQL |
| Presto/Trino | Federated query access to Pinot via Presto connector |
| Grafana | Grafana data source plugin for Pinot metrics |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Pinot REST API](openapi/apache-pinot-rest-api.yaml)

### JSON Schema

- [SQL Query Request](json-schema/apache-pinot-sql-query-request-schema.json)
- [SQL Query Response](json-schema/apache-pinot-sql-query-response-schema.json)
- [Table Config](json-schema/apache-pinot-table-config-schema.json)
- [Schema](json-schema/apache-pinot-schema-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache Pinot JSON Structures](json-structure/)

### JSON-LD

- [Apache Pinot Context](json-ld/apache-pinot-context.jsonld)

### Examples

- [Apache Pinot Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Analytics Workflow](capabilities/pinot-workflow.yaml) | Apache Pinot | 8 | Data Analyst, Platform Engineer |

## Vocabulary

- [Apache Pinot Vocabulary](vocabulary/apache-pinot-vocabulary.yaml) — Unified taxonomy mapping OLAP analytics resources, actions, workflows, and personas

## Rules

- [Apache Pinot Spectral Rules](rules/apache-pinot-spectral-rules.yml) — Rules enforcing Apache Pinot API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
