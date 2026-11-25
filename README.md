🇺🇸 **English** · 🇪🇸 [Español](README.es.md)

# Erick Guarnizo

**Cloud & DevOps Engineer focused on infrastructure automation, Linux, security and reliability.**

Ecuador · [LinkedIn](https://www.linkedin.com/in/erick-g-571a7b3b4)

**Featured:** [ANDES-HOMELAB](https://github.com/GUAR-NIX/ANDES-HOMELAB), an infrastructure, security and recovery lab ·
[Ecuador Labor Observatory](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec), an automated data platform
([live app](https://observatorio-laboral-ec.streamlit.app/?lang=en))

| Measured result | Evidence |
|---|---|
| **7 min 19 s** to rebuild a destroyed lab server from Git with Terraform and Ansible | [ANDES: decision](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/docs/adr/ADR-0005-terraform-bpg.md), [script](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/scripts/reconstruir-servidor.sh) |
| **6 of 6** disaster recovery drills passed; VM restored in 5 min 19 s | [ANDES: drill log](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/docs/dr/resultados-simulacros.md) |
| **−79%** vulnerabilities (19,784 → 4,062) in one patching cycle | [ANDES: guide](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/docs/GUIA-DEL-PROYECTO.md) |
| **0 errors in 39,842 requests** during a Kubernetes rolling upgrade (14 errors before the drain fix) | [Climate API: report](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/blob/main/kubernetes-api-clima/reports/rolling_update.json) |
| **20 of 20** official labor rates reproduced and tested by a weekly pipeline | [Observatory: runs](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec-pipeline.yml) |

## Featured projects

### [ANDES-HOMELAB](https://github.com/GUAR-NIX/ANDES-HOMELAB) · infrastructure, security and recovery

[![CI](https://github.com/GUAR-NIX/ANDES-HOMELAB/actions/workflows/ci.yml/badge.svg)](https://github.com/GUAR-NIX/ANDES-HOMELAB/actions/workflows/ci.yml)

A **lab** that reproduces a small company's infrastructure on one laptop: 10 VMs on Proxmox, 6 segmented VLANs, Active
Directory, internal PKI, Terraform, Ansible, GitHub Actions, Prometheus and Grafana, a Wazuh SIEM and tested backups.

[Code](https://github.com/GUAR-NIX/ANDES-HOMELAB/tree/main/ansible) ·
[Architecture](https://github.com/GUAR-NIX/ANDES-HOMELAB#architecture) ·
[Decisions](https://github.com/GUAR-NIX/ANDES-HOMELAB/tree/main/docs/adr) ·
[Incident report](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/docs/incidents/INC-0001.md) ·
[Demo video, 3:26](https://youtu.be/rV9RyCcJ3Nk)

### [Ecuador Labor Observatory](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec) · automated data platform

[![CI](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec.yml/badge.svg)](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec.yml)
[![Weekly pipeline](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec-pipeline.yml/badge.svg)](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/actions/workflows/observatorio-laboral-ec-pipeline.yml)

Public survey microdata to PostgreSQL, dbt, a containerized API and a public app, run by GitHub Actions on free cloud
tiers, with a model quality gate, 40 dbt tests and a drift monitor.

[Live app](https://observatorio-laboral-ec.streamlit.app/?lang=en) ·
[Code](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec/src/observatorio) ·
[Tests](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec/tests) ·
[Architecture](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec#architecture) ·
[Decisions](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec/docs/adr)

## What I bring to a team

- **Rebuildable infrastructure.** Servers are declared in Terraform and configured with Ansible; a rebuild is a
  timed, repeatable procedure.
- **Reliability that is measured.** Baselines before changes, timed recovery drills, load tests and a 99% availability
  objective in Prometheus.
- **Security as part of the work.** Deny-by-default networks, hardening, patching, secret scanning in CI and a
  simulated incident handled end to end with a written report.
- **Documentation others can operate from.** Architecture decision records, runbooks, a change log and what failed.

## More cloud and DevOps work

| Project | Stack | Measured |
|---|---|---|
| [Climate API on Kubernetes](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/kubernetes-api-clima) | kind, Helm, HPA, Prometheus, Grafana | 68.5 → 476.3 requests/s from 1 to 4 replicas |
| [Serverless earthquake alerts](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/serverless-sismos-localstack) | Terraform, Lambda, DynamoDB, SNS (AWS emulated with LocalStack) | 2,080 repeated events absorbed with 0 duplicates |
| [GitHub activity streaming](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/streaming-github-redpanda-spark) | Redpanda, Spark, Delta Lake | 0 duplicates and 0 lost after 3 `docker kill` |
| [Scheduled ingestion with Airflow](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/airflow-apis-postgres) | Airflow, PostgreSQL, Docker Compose | 410 backfill runs completed |

These run locally or on emulators; the repositories state what was deployed and what was not.

## Secondary skills: data engineering and AI

| Repository | Focus |
|---|---|
| [PORTAFOLIO-CLOUD](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD) | Seven cloud, DevOps and data engineering projects |
| [PORTAFOLIO-SQL](https://github.com/GUAR-NIX/PORTAFOLIO-SQL) | Data warehouses and query tuning in SQL Server and PostgreSQL |
| [PORTAFOLIO-PYTHON](https://github.com/GUAR-NIX/PORTAFOLIO-PYTHON) | Reproducible analysis of public data |
| [PORTAFOLIO-ML](https://github.com/GUAR-NIX/PORTAFOLIO-ML) | Machine learning with temporal validation and APIs |
| [PORTAFOLIO-IA](https://github.com/GUAR-NIX/PORTAFOLIO-IA) | Local LLM applications evaluated against baselines |

## Tools used in these repositories

**Infrastructure:** Linux (Ubuntu), Windows Server, Proxmox VE, OPNsense, WireGuard ·
**Automation:** Terraform, Ansible, GitHub Actions, Docker, Kubernetes, Helm ·
**Security and observability:** Wazuh, Trivy, gitleaks, Prometheus, Grafana ·
**Languages and data:** Python, Bash, SQL, PostgreSQL, SQL Server, Airflow, Spark, dbt

Documentation inside the projects is mostly in Spanish; every project page has an English version or summary.
