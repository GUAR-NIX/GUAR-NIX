# Hola, soy Erick Guarnizo 👋

**Infraestructura · Ciberseguridad · DevOps · Datos e IA** — Ecuador 🇪🇨

Construyo plataformas completas y las demuestro con datos medidos: redes segmentadas, identidad, automatización con
código, detección de ataques, copias que se prueban de verdad… y, del otro lado, pipelines de datos, modelos de
machine learning e IA aplicada con modelos locales.

> *«Todo lo que se afirma, se midió.»* Cada proyecto incluye sus resultados, su documentación y lo que salió mal.

---

## 🏢 Proyecto destacado: [ANDES-HOMELAB](https://github.com/GUAR-NIX/ANDES-HOMELAB)

**La infraestructura completa de una empresa, construida, automatizada y defendida en un solo portátil.**

Proxmox VE · OPNsense (6 VLAN + VPN WireGuard) · Active Directory · PKI propia · Terraform · Ansible ·
GitHub Actions · Docker · Prometheus + Grafana · SIEM Wazuh · Proxmox Backup Server

| Lo demostrado | Medido |
|---|---|
| Servidor destruido y reconstruido solo desde git | **7 min 19 s** |
| Ataque simulado detectado por el SIEM | **5 s** |
| Vulnerabilidades tras un ciclo de parcheo | **−79 %** |
| Endurecimiento de servidores (Lynis) | **63 → 83** |
| Simulacros de recuperación ante desastres | **6 / 6** superados |

🎬 [Video de demostración (3:26)](https://youtu.be/rV9RyCcJ3Nk) ·
📖 [Guía completa fase por fase](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/docs/GUIA-DEL-PROYECTO.md) ·
🔎 [Informe del incidente simulado](https://github.com/GUAR-NIX/ANDES-HOMELAB/blob/main/docs/incidents/INC-0001.md)

---

## 📊 Proyecto destacado de datos: [Observatorio laboral del Ecuador](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/tree/main/observatorio-laboral-ec)

**De los microdatos de la encuesta de empleo del INEC a un modelo de machine learning en producción.**

Python · PostgreSQL (Neon) · dbt · GitHub Actions · Power BI · LightGBM + SHAP · FastAPI · Docker · MLflow · Streamlit

| Lo demostrado | Medido |
|---|---|
| Tasas oficiales del INEC reproducidas desde 1,16 M de registros | **al décimo** |
| Modelo de informalidad en 6 meses que nunca vio | **AUC 0,910** · tasa estimada a 0,4 pp de la real |
| Pronóstico del desempleo con backtesting | **0,24 pp** de error, 26 % mejor que la referencia |
| Tests de datos y de código | **40 dbt + 45 Python**, en verde en cada push |
| Coste de la plataforma | **0 USD** |

🧮 [App en vivo](https://observatorio-laboral-ec.streamlit.app) ·
📈 [Tablero público](https://datastudio.google.com/reporting/a932a4c2-ecc6-4148-afd1-df75157ebdb0) ·
📖 [Guía paso a paso](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD/blob/main/observatorio-laboral-ec/docs/GUIA_PASO_A_PASO.md)

---

## 📂 Portafolio

| Proyecto | De qué trata | Tecnologías |
|---|---|---|
| 🏢 [ANDES-HOMELAB](https://github.com/GUAR-NIX/ANDES-HOMELAB) | Infraestructura empresarial completa: red, identidad, IaC, SIEM y recuperación ante desastres | Proxmox, OPNsense, AD, Terraform, Ansible, Wazuh |
| ☁️ [PORTAFOLIO-CLOUD](https://github.com/GUAR-NIX/PORTAFOLIO-CLOUD) | Ingeniería de datos y cloud: el observatorio laboral de punta a punta, orquestación, streaming, lakehouse, Kubernetes y serverless | dbt, LightGBM, FastAPI, Airflow, Dagster, Spark, Iceberg + Trino, Helm, AWS + Terraform |
| 🤖 [PORTAFOLIO-IA](https://github.com/GUAR-NIX/PORTAFOLIO-IA) | IA aplicada con LLM locales: agente con herramientas, RAG de la ley laboral del Ecuador, extracción de facturas | Ollama, RAG, Python |
| 📈 [PORTAFOLIO-ML](https://github.com/GUAR-NIX/PORTAFOLIO-ML) | Machine learning con datos reales: CLV, demanda, fraude, visión por computadora, recomendador | scikit-learn, Python, Jupyter |
| 🗄️ [PORTAFOLIO-SQL](https://github.com/GUAR-NIX/PORTAFOLIO-SQL) | Data warehouses con SCD2 y carga incremental, grafos, RFM y cohortes, tuning de rendimiento | SQL Server, PostgreSQL |
| 🐍 [PORTAFOLIO-PYTHON](https://github.com/GUAR-NIX/PORTAFOLIO-PYTHON) | Análisis de datos públicos: clima de Ecuador, mercado laboral ENEMDU, sismicidad, criminalidad | Python, pandas, Jupyter |
| 🛡️ [HERRAMIENTAS-DE-CIBERSEGURIDAD](https://github.com/GUAR-NIX/HERRAMIENTAS-DE-CIBERSEGURIDAD) | Herramientas de ciberseguridad | Seguridad |

---

## 🧰 Tecnologías

**Infraestructura y redes**
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**Automatización y DevOps**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Seguridad y observabilidad**
![Wazuh](https://img.shields.io/badge/Wazuh_SIEM-3595F9?style=flat-square)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)

**Datos, cloud e IA**
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

## 🎯 Cómo trabajo

- **Medir antes y después**: sin línea base no hay mejora demostrable.
- **Todo como código**: si no está en git, no existe y no se puede reconstruir.
- **Probar lo que importa**: copias restauradas, ataques simulados, servidores destruidos a propósito.
- **Documentar para el siguiente**: decisiones (ADR), procedimientos (runbooks) y lecciones aprendidas.

---

*Abierto a oportunidades en infraestructura, ciberseguridad, DevOps y datos.*
