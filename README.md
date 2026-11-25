🇺🇸 **English** · 🇪🇸 [Español](README.es.md)

# Erick Guarnizo

**Data Engineer focused on reliable pipelines, data quality and reproducible infrastructure.**

Ecuador · [LinkedIn](https://www.linkedin.com/in/erick-g-571a7b3b4)

**Featured:** [Ecuador Labor Observatory](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec), an automated data platform
([live app](https://observatorio-laboral-ec.streamlit.app/?lang=en)) ·
[GitHub activity streaming](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/streaming-github-redpanda-spark), Kafka API, Spark and Delta Lake

| Measured result | Evidence |
|---|---|
| **20 of 20** official labor rates reproduced and tested by a weekly pipeline | [Observatory: runs](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec-pipeline.yml) |
| **0 duplicates and 0 lost** in bronze and silver after 3 `docker kill` (2.9 million messages) | [Streaming: verification](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/blob/main/streaming-github-redpanda-spark/reports/metricas/recuperacion/verificacion.json) |
| **41.2 million** trips loaded; source = fact + quarantine, difference **0** in 12 months | [Taxi warehouse: reconciliation](https://github.com/GUAR-NIX/PORTAFOLIO-SQL/blob/main/dw-taxis-nyc-sqlserver/reports/tablas/cuadre_fuente.csv) |
| **410** backfill runs and 6,405 logged quality checks | [Airflow: results](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/blob/main/airflow-apis-postgres/reports/resultados.json) |
| **92.50–99.96%** fewer pages read in nine query tuning experiments | [SQL tuning: experiments](https://github.com/GUAR-NIX/PORTAFOLIO-SQL/blob/main/tuning-sqlserver-citibike/reports/tablas/experimentos_tuning.csv) |

## Featured projects

### [Ecuador Labor Observatory](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec) · automated data platform

[![CI](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec.yml/badge.svg)](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec.yml)
[![Weekly pipeline](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec-pipeline.yml/badge.svg)](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec-pipeline.yml)

Public survey microdata to PostgreSQL and dbt, run every week by GitHub Actions on free cloud tiers: incremental dbt,
37 dbt tests with audited publication, freshness checks, a containerized API and a public app.

[Live app](https://observatorio-laboral-ec.streamlit.app/?lang=en) ·
[Code](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec/src/observatorio) ·
[dbt models](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec/dbt) ·
[Tests](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec/tests) ·
[Architecture](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec#architecture) ·
[Decisions](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec/docs/adr)

### [GitHub activity streaming](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/streaming-github-redpanda-spark) · Redpanda, Spark, Delta Lake

[![CI](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/streaming-github-redpanda-spark.yml/badge.svg)](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/streaming-github-redpanda-spark.yml)

11.4 million public events replayed through bronze, silver and gold layers with event-time windows, bounded deduplication
and idempotent writes. Local, on one node.

[Code](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/streaming-github-redpanda-spark/src/streaming_gh) ·
[Tests](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/streaming-github-redpanda-spark/tests) ·
[Measurements](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/streaming-github-redpanda-spark/reports)

## What I bring to a team

- **Pipelines that can run twice.** Idempotent loads, watermarks, atomic partition switches and backfills that resume.
- **Data that reconciles.** Control totals against the source, quarantine with the reason, and tests that stop publication.
- **Infrastructure I can operate.** Terraform, Ansible, Docker, CI and recovery drills, shown in
  [ANDES-HOMELAB](https://github.com/GUAR-NIX/ANDES-HOMELAB): a lab server rebuilt from Git in 7 min 19 s and 6 of 6 recovery drills passed.
- **Decisions in writing.** Architecture decision records, what failed and how each result was measured.

## More data engineering work

| Project | Stack | Measured |
|---|---|---|
| [Scheduled ingestion](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/airflow-apis-postgres) | Airflow, PostgreSQL, Docker Compose | 384 daily and 26 yearly runs, with checks that stop the DAG |
| [Lakehouse](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/lakehouse-iceberg-trino-nessie) | Iceberg, Trino, Nessie, MinIO | A defective day fails 3 of 7 checks and never reaches `main` |
| [Asset-based data stack](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/modern-data-stack-dagster-dbt) | Dagster, dbt, DuckDB, MinIO | 177.5 million observations, 45 quality checks |
| [NYC taxi warehouse](https://github.com/GUAR-NIX/PORTAFOLIO-SQL/tree/main/dw-taxis-nyc-sqlserver) | SQL Server, columnstore, partitioning | Partition `SWITCH` in 12–221 ms |
| [SQL performance lab](https://github.com/GUAR-NIX/PORTAFOLIO-SQL/tree/main/tuning-sqlserver-citibike) | SQL Server, execution plans | 260 measured runs |
| [Serverless earthquake alerts](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/serverless-sismos-localstack) | Terraform, Lambda, DynamoDB (AWS emulated) | 2,080 repeated events, 0 duplicates |

Except for the observatory, these run locally or on emulators; each repository states what was deployed and what was not.

## Repositories

| Repository | Focus |
|---|---|
| [PORTAFOLIO-CLOUD](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD) | Seven data engineering and cloud projects |
| [PORTAFOLIO-SQL](https://github.com/GUAR-NIX/PORTAFOLIO-SQL) | Data warehouses and query tuning in SQL Server and PostgreSQL |
| [PORTAFOLIO-PYTHON](https://github.com/GUAR-NIX/PORTAFOLIO-PYTHON) | Reproducible analysis of public data |
| [ANDES-HOMELAB](https://github.com/GUAR-NIX/ANDES-HOMELAB) | Infrastructure, security and disaster recovery lab |
| [PORTAFOLIO-ML](https://github.com/GUAR-NIX/PORTAFOLIO-ML) | Machine learning with temporal validation and APIs |
| [PORTAFOLIO-IA](https://github.com/GUAR-NIX/PORTAFOLIO-IA) | Local LLM applications evaluated against baselines |

## Tools used in these repositories

**Languages:** Python, SQL, T-SQL, Bash ·
**Data:** PostgreSQL, SQL Server, dbt, Airflow, Dagster, Spark, Redpanda (Kafka API), Delta Lake, Iceberg, Trino, DuckDB ·
**Infrastructure:** Docker, Kubernetes, Terraform, Ansible, GitHub Actions, Linux ·
**Security and observability:** Wazuh, Trivy, gitleaks, Prometheus, Grafana

Documentation inside the projects is mostly in Spanish; every project page has an English version or summary.
