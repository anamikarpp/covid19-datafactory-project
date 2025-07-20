# Azure Data Factory Project – COVID-19 Data Engineering Pipeline

🚀 This project showcases a complete end-to-end Azure Data Factory (ADF) pipeline for ingesting, transforming, and loading COVID-19 datasets. The pipeline includes data validation, transformation, storage integration, Databricks, and Power BI integration.

---

## 🛠️ Tech Stack

- **Azure Data Factory (ADF)**
- **Azure Data Lake Gen2**
- **Azure SQL Database**
- **Azure Databricks**
- **Power BI**
- **Azure DevOps (for CI/CD)**

---

## 🧪 Scenarios Implemented

1. ✅ **Triggering pipelines** when a new file becomes available.
2. 🔍 **Validating file contents** before processing.
3. 🧹 **Deleting source files** post-processing.
4. ⏱ **Schedule and tumbling window triggers**
5. 📥 **Ingesting external data** (e.g., from HTTP)
6. 🔄 **Transformations**
   - Filter
   - Pivot
   - Lookup (left outer join)
7. 🧩 **Databricks integration**
   - Mounting Azure Data Lake
   - Running notebooks via job clusters
8. 🏁 **Production-ready pipelines**
9. 📊 **Power BI dashboards**

---

## 🔁 CI/CD Process

- Used Azure DevOps for feature branching and pull requests.
- Implemented Dev → QA → Prod pipeline promotions.
- Used parameterized pipelines for environment-specific values.

---

## 📸 Screenshots

Screenshots are included in the repo to illustrate:
- Pipeline configurations
- Trigger setup
- Data Lake and Databricks mounting
- Parameter passing
- Power BI integration

---

