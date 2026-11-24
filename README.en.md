🇪🇸 [Español](README.md) · 🇬🇧 **English**

# Hi, I'm Erick Guarnizo 👋

**Infrastructure · Cybersecurity · DevOps · Data & AI** — Ecuador 🇪🇨

I build complete platforms and prove them with measured data: segmented networks, identity, automation as code,
attack detection, backups that are actually tested… and, on the other side, data pipelines, machine learning models
and applied AI with local models.

> *"Everything claimed here was measured."* Every project includes its results, its documentation and what went wrong.

---

## 🏢 Featured project: [ANDES-HOMELAB](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/README.en.md)

**A company's entire infrastructure, built, automated and defended on a single laptop.**

Proxmox VE · OPNsense (6 VLANs + WireGuard VPN) · Active Directory · own PKI · Terraform · Ansible ·
GitHub Actions · Docker · Prometheus + Grafana · Wazuh SIEM · Proxmox Backup Server

| What was demonstrated | Measured |
|---|---|
| Server destroyed and rebuilt from git alone | **7 min 19 s** |
| Simulated attack detected by the SIEM | **5 s** |
| Vulnerabilities after one patching cycle | **−79%** |
| Server hardening (Lynis) | **63 → 83** |
| Disaster recovery drills | **6 / 6** passed |

🎬 [Demo video (3:26, in Spanish)](https://youtu.be/rV9RyCcJ3Nk) ·
📖 [Full phase-by-phase guide (Spanish)](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/docs/GUIA-DEL-PROYECTO.md) ·
🔎 [Simulated incident report (Spanish)](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/docs/incidents/INC-0001.md)

---

## 📊 Featured data project: [Ecuador Labor Observatory](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/blob/main/observatorio-laboral-ec/README.en.md)

**From the microdata of Ecuador's national employment survey (INEC) to a machine learning model in production.**

Python · PostgreSQL (Neon) · dbt · GitHub Actions · Power BI · LightGBM + SHAP · FastAPI · Docker · MLflow · Streamlit

| What was demonstrated | Measured |
|---|---|
| Official INEC rates reproduced from the microdata | **20 out of 20**, to one decimal (5 months) |
| Informality model on 6 months it had never seen | **AUC 0.910** · estimated rate within 0.4 pp of the real one |
| Unemployment forecast with backtesting | **0.24 pp** error, 26% better than the baseline |
| Automated tests | **50** in Python and **40** in dbt (the latter in the weekly pipeline) |
| Platform cost | **0 USD** |

🧮 [Live app](https://observatorio-laboral-ec.streamlit.app/?lang=en) ·
📈 [Public dashboard (Spanish)](https://datastudio.google.com/reporting/a932a4c2-ecc6-4148-afd1-df75157ebdb0) ·
📖 [Step-by-step guide (Spanish)](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/blob/main/observatorio-laboral-ec/docs/GUIA_PASO_A_PASO.md)

---

## 📂 Portfolio

| Project | What it is about | Technologies |
|---|---|---|
| 🏢 [ANDES-HOMELAB](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/README.en.md) | Complete company infrastructure: network, identity, IaC, SIEM and disaster recovery | Proxmox, OPNsense, AD, Terraform, Ansible, Wazuh |
| ☁️ [PORTAFOLIO-CLOUD](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/blob/main/README.en.md) | Data engineering and cloud: the labor observatory end to end, orchestration, streaming, lakehouse, Kubernetes and serverless | dbt, LightGBM, FastAPI, Airflow, Dagster, Spark, Iceberg + Trino, Helm, AWS + Terraform |
| 🤖 [PORTAFOLIO-IA](https://github.com/GUAR-NIX/PORTAFOLIO-IA/blob/main/README.en.md) | Applied AI with local LLMs: tool-using agent, RAG over Ecuador's labor law, invoice extraction | Ollama, RAG, Python |
| 📈 [PORTAFOLIO-ML](https://github.com/GUAR-NIX/PORTAFOLIO-ML/blob/main/README.en.md) | Machine learning with real data: CLV, demand, fraud, computer vision, recommender | scikit-learn, Python, Jupyter |
| 🗄️ [PORTAFOLIO-SQL](https://github.com/GUAR-NIX/PORTAFOLIO-SQL/blob/main/README.en.md) | Data warehouses with SCD2 and incremental loads, graphs, RFM and cohorts, performance tuning | SQL Server, PostgreSQL |
| 🐍 [PORTAFOLIO-PYTHON](https://github.com/GUAR-NIX/PORTAFOLIO-PYTHON/blob/main/README.en.md) | Analysis of public data: Ecuador's climate, labor market (ENEMDU), seismicity, crime | Python, pandas, Jupyter |
| 🛡️ [HERRAMIENTAS-DE-CIBERSEGURIDAD](https://github.com/GUAR-NIX/HERRAMIENTAS-DE-CIBERSEGURIDAD) | Cybersecurity tools | Security |

---

## 🧰 Technologies

**Infrastructure and networking**
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**Automation and DevOps**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Security and observability**
![Wazuh](https://img.shields.io/badge/Wazuh_SIEM-3595F9?style=flat-square)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)

**Data, cloud and AI**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![LightGBM](https://img.shields.io/badge/LightGBM-2C7BB6?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

---

## 🎯 How I work

- **Measure before and after**: without a baseline there is no proven improvement.
- **Everything as code**: if it is not in git, it does not exist and cannot be rebuilt.
- **Test what matters**: restored backups, simulated attacks, servers destroyed on purpose.
- **Document for the next person**: decisions (ADRs), procedures (runbooks) and lessons learned.

---

*Open to opportunities in infrastructure, cybersecurity, DevOps and data.*
