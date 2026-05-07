<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=3B82F6&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B+I'm+Navin+Kumar+Nagisetty;Data+Engineer+%7C+Healthcare+%7C+Retail+%7C+Finance;Databricks+%7C+AWS+%7C+dbt+%7C+Airflow+%7C+Spark;Finding+Patterns+That+Change+Decisions" alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/navinnagisetty/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:navinnagisetty@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/navinnagisetty"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://california-housing-ml-ab74.onrender.com"><img src="https://img.shields.io/badge/Live_API-00C851?style=for-the-badge&logo=render&logoColor=white"/></a>
  <a href="https://public.tableau.com/app/profile/navin.kumar.nagisetty/viz/GhostNetworkDetectionMedicareProviderAnalysis/GhostNetworkDetectionMedicareProviderDirectoryAnalysis"><img src="https://img.shields.io/badge/Live_Dashboard-E97627?style=for-the-badge&logo=tableau&logoColor=white"/></a>
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=navinnagisetty&style=for-the-badge&color=3B82F6" alt="Profile Views"/>
</div>

---

## 👨‍💻 About Me

I'm a **Data Analyst & Data Engineer** based in Fairfield, CT, graduated from **Fairfield University**.

I don't build tutorials. I find real problems disclosed in SEC filings and government reports — and build the systems that address them.

- 🏥 Built a ghost network detector that found **57.6% of Medicare mental health providers are unreachable** — a problem the Senate Finance Committee formally disclosed in 2023
- 🏪 Built a demand forecasting lakehouse that quantified **$2.75M in Walmart inventory risk** — grounded in their SEC-disclosed material financial risk
- ⚡ Processing data at scale with **PySpark, AWS Glue, Delta Lake** across millions of records
- 🤖 Integrating **LLMs into production pipelines** — Llama 3 and Claude Haiku generating actionable alerts from structured data
- 💼 Open to **Data Engineer** and **Data Analyst** roles

---

## 🛠️ Tech Stack

**Lakehouse & Data Engineering**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Cloud & Warehousing**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=google-bigquery&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Athena](https://img.shields.io/badge/Athena-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

**ML & AI**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logoColor=white)
![Llama3](https://img.shields.io/badge/Llama_3-7B3F00?style=for-the-badge&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Haiku-D97706?style=for-the-badge&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**Languages & Visualization**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 🚀 Projects

---

### 🏥 Ghost Network Detection — AWS Healthcare Compliance Pipeline
> 57.6% of listed Medicare mental health providers are unreachable. This system finds them.

The Senate Finance Committee (May 2023) formally disclosed that more than 80% of Medicare Advantage mental health providers were unreachable when patients called. CMS 2025 mandates 90% compliance. This project ingests the full nationwide Medicare provider directory and detects ghost providers at scale.

| Metric | Result |
|--------|--------|
| Providers scored | **2,857,460** — full US Medicare directory |
| NPPES ground truth | **8M+** licensed providers |
| Mental health ghost rate | **57.6%** — 38x higher than overall average |
| Deactivated NPIs still listed | **6,900 providers** |
| Providers sharing one phone | **6,803** — detected via graph analysis |
| Highest ghost rate ZIP | **84.6%** — ZIP 68065 Nebraska |
| Bedrock AI compliance alerts | **10** plain-English audit reports |
| dbt tests | **11 / 11 passing** |
| Orchestration | **Step Functions** · 5-step weekly pipeline |

**Stack:** AWS Glue · Athena · Bedrock · Step Functions · NetworkX · dbt · Tableau · FastAPI

[![GitHub](https://img.shields.io/badge/View_Project-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Navinnagisetty/ghost-network-detection)
[![Live Dashboard](https://img.shields.io/badge/Live_Dashboard-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/navin.kumar.nagisetty/viz/GhostNetworkDetectionMedicareProviderAnalysis/GhostNetworkDetectionMedicareProviderDirectoryAnalysis)

---

### 🏪 Walmart Demand Intelligence — Databricks Lakehouse Pipeline
> Production-grade demand forecasting grounded in Walmart's SEC-disclosed inventory risk

Walmart disclosed in its 2025 Annual Report that inventory inaccuracy is a **material financial risk** against a **$64.5B inventory base**. This project builds the system to address it.

| Metric | Result |
|--------|--------|
| Data processed | **58,327,370 rows** — 4 Delta tables |
| Features engineered | **25** lag, rolling, price, event signals |
| Revenue at risk quantified | **$2.75M** across 30,490 store-item profiles |
| ML models trained | **10 store-specific XGBoost models in parallel** |
| RMSE improvement | **39.44% avg** over naive baseline |
| AI alerts | **Llama 3** plain-English alerts via Mosaic AI |
| dbt tests | **11 / 11 passing** |
| Orchestration | **8-task Airflow DAG** · scheduled weekly |

**Stack:** Databricks · PySpark · Delta Lake · MLflow · dbt · Airflow · Llama 3 · Databricks SQL

[![GitHub](https://img.shields.io/badge/View_Project-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Navinnagisetty/walmart-demand-forecasting)

---

### 🏠 California Housing Price Predictor — Live API
> XGBoost model predicting California house prices, deployed as a live REST API

- **R² = 0.8208** — engineered 8 custom features, coastal proximity became #1 predictor
- **K-Means clustering** segmented California into 4 distinct housing market types
- API auto-calculates all 19 features from just 8 raw inputs
- Deployed live on **Render.com** — callable right now

[![Live API](https://img.shields.io/badge/Live_API-00C851?style=for-the-badge&logo=render&logoColor=white)](https://california-housing-ml-ab74.onrender.com)
[![API Docs](https://img.shields.io/badge/API_Docs-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://california-housing-ml-ab74.onrender.com/docs)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/navinnagisetty/california-housing-ml)

---

### 🏥 Healthcare Analytics & AI Assistant Platform
> End-to-end analytics platform on Snowflake with NL-to-SQL AI assistant

- **Snowflake + Snowpark** processing 1.5M+ records daily
- NL-to-SQL AI assistant converts plain English to SQL queries
- 15+ Power BI dashboards serving 200+ stakeholders
- Healthcare KPIs: RAF scores, CARR, IP/OP cost analysis

[![Live Dashboard](https://img.shields.io/badge/Live_Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiMmFmYTU1N2EtN2Y0OC00YzRmLTk0Y2EtNDM5ZWZhN2RjNzViIiwidCI6ImM5NTZmZjRjLTBjODQtNDVkNi05Yjk1LWQxNDk3ZDAyNmNjYiJ9)

---

### 📊 GCP Stock ETL Pipeline
> End-to-end stock price pipeline on Google Cloud Platform

- **Airflow + BigQuery + dbt + Looker Studio** full modern stack
- Automated daily ingestion, transformation, and visualization

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Navinnagisetty/gcp-stock-etl-pipeline)

---

### 📋 ETL Audit Dashboard
> Power BI dashboard monitoring ETL pipeline performance

- **96.5% success rate** tracked across 1,052 jobs
- Job-level breakdown with user attribution and historical trends

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=navinnagisetty&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=navinnagisetty&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=navinnagisetty&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</div>

---

## 🤝 Let's Connect

Actively looking for **Data Engineer** and **Data Analyst** roles. I find real problems in government reports and SEC filings — then build the systems that address them.

📧 navinnagisetty@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/navinnagisetty/)
🌐 [Live ML API](https://california-housing-ml-ab74.onrender.com)
📊 [Live Tableau Dashboard](https://public.tableau.com/app/profile/navin.kumar.nagisetty/viz/GhostNetworkDetectionMedicareProviderAnalysis/GhostNetworkDetectionMedicareProviderDirectoryAnalysis)
