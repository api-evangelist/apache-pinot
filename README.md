# Apache Pinot (apache-pinot)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
