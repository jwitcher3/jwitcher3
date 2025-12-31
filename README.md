# 👋 Hey, I’m James Witcher

Marketing Data Scientist building **forecasting, experimentation, and causal measurement systems** for retail/eCommerce — turning messy behavioral data into decisions.  
Previously: Nike • adidas • Intel | Python • SQL • Databricks • Snowflake • Streamlit

🔗 [LinkedIn](https://www.linkedin.com/in/james-witcher/) • ✉️ [Email](mailto:james.witcher@outlook.com) • 🧭 [Retail Trend Tracker (live)](https://retail-trend-tracker.vercel.app/)


### 🔎 Data & Reuse Note

> **Note:** Everything here uses publicly available and/or synthetic data, designed as reusable templates that can be adapted to real internal datasets.

---

## ⭐ Featured Projects

### 🧪 M5 Causal Lift (Incrementality Sandbox)
**Repo:** https://github.com/jwitcher3/m5-causal-lift  
End-to-end incrementality sandbox on **M5-style simulated retail data** with known ground truth.  
- Methods: **DiD / Event Study** • **Synthetic Control (ridge SCM, optional log1p)**  
- Trust checks: pre-trend checks • diagnostics (pre-fit RMSE, stability CV) • **placebo tests** (fake treatment dates/windows)  
- Includes a **Streamlit app** + donor weight interpretability  
- Run: `./scripts/demo.sh` (launches Streamlit locally)

### 📈 Retail Trend Tracker (live)
**Live:** https://retail-trend-tracker.vercel.app/  
**Repo:** https://github.com/jwitcher3/retail-trend-tracker  
Deployed dashboard surfacing retail/sneaker trend signals to quickly see “what’s up / what’s down.”  
- Focus: franchise-level trend monitoring and lightweight public dashboards  
- Stack: Python • JavaScript • Plotly • Vercel

### 🏛️ EDGAR Retail — SEC Filings → Clean Quarterly Dataset (WIP)
**Repo:** https://github.com/jwitcher3/edgar-retail  
Hands-on ETL project that pulls messy public **SEC EDGAR filings (10-K / 10-Q) + XBRL financials** for selected retail brands, then reshapes them into **tidy quarterly tables** for analysis.  
- **Outputs:** DuckDB + Parquet dataset combining financials (revenue, inventory, gross profit) with simple filing text signals  
  (mentions of **inventory**, **promotions/markdowns**, **guidance**, etc.)  
- **Use case:** quickly spot “pressure quarters” where the numbers *and* management language indicate stress  
- **End goal:** interactive dashboard to pick a company, view trends over time, and flag quarters worth investigating  

---

## 🧰 Toolbox
**Methods:** forecasting • experimentation • causal inference • segmentation • attribution/CLV  
**Build:** dashboards • data apps • pipelines • reusable analytics templates  
**Stack:** Python • SQL • Databricks • Snowflake • JavaScript • Streamlit • Plotly • Azure

---

## 🤝 Open to Collaborate On
- Retail, eCommerce, and product analytics projects
- Public dashboards, LLM-enabled insights, and visual storytelling
- Data science education or training resources

---

<details>
  <summary>📊 GitHub Stats</summary>

  ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jwitcher3&show_icons=true&theme=default&hide_rank=true)  
  ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jwitcher3&layout=compact&hide=html&theme=default)
</details>

---

## 🏷️ Tech
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-005C84?style=flat&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Databricks](https://img.shields.io/badge/Databricks-E36C00?style=flat&logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=000000)
![Parquet](https://img.shields.io/badge/Parquet-000000?style=flat&logo=apache&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Make](https://img.shields.io/badge/Make-000000?style=flat&logo=gnu&logoColor=white)

<!---
jwitcher3/jwitcher3 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
