# Hi there, I'm Abdelaal! 👋
### Data Engineer | Specializing in Modern Data Stack & Cloud Architectures

I am a passionate Data Engineer focused on building robust, scalable, and cost-optimized end-to-end data pipelines. I love transforming raw data into actionable insights using cloud technologies and dimensional modeling.

---

## 📕 Top Projects I've Contributed To

### 🪙 [Gold Market & Inflation Analytics Platform](https://github.com/YOUR_USERNAME/Gold-Market-Data-Pipeline)
An end-to-end cloud data pipeline engineered on **Azure** and **Databricks** to ingest, process, and analyze historical and real-time gold market pricing against economic inflation indicators.
*   **Architecture:** Built using the **Medallion Architecture** (Bronze ──> Silver ──> Gold) to ensure data reliability and clean transformations.
*   **Data Processing:** Ingested raw JSON data using Python, performed advanced feature engineering (Daily Spread/Volatility calculation) via **PySpark**, and structured the final layers using **Spark SQL**.
*   **Dimensional Modeling:** Modeled a high-performance **Star Schema** consisting of **3 Dimension Tables** (`dim_gold_date`, `dim_gold_inflation`, `dim_gold_market_status`) surrounding a central Fact table.
*   **BI & Serving:** Connected **Power BI via Import Mode** to achieve maximum dashboard performance and minimize runtime cloud compute costs.

---

### ✈️ [AeroDB: Aviation & Flight Delay Infrastructure](https://github.com/YOUR_USERNAME/AeroDB)
A scalable data infrastructure project designed to handle high-velocity aviation data, flight delays, and live weather conditions.
*   **Architecture:** Implemented a **Galaxy Schema** to link multiple complex fact tables (`FACT_FLIGHT_DELAY`) with shared dimensions like `DIM_AIRPORT`.
*   **Streaming & Storage:** Designed a hybrid storage strategy utilizing **Snowflake** for historical data warehousing and **TimescaleDB** for time-series weather logs, with data ingestion powered by the OpenSky API.

---

## 🛠️ Tech Stack & Toolkit

*   **Cloud Platforms:** Microsoft Azure (Synapse, Databricks, Storage Accounts)
*   **Data Warehouses & Lakes:** Delta Lake, Snowflake, SQL Server (SSMS)
*   **Data Processing & Transformation:** PySpark, Spark SQL, Python, dbt
*   **BI & Analytics:** Power BI (Import & DirectQuery optimization)
*   **Version Control:** GitHub

---

## 📈 My GitHub Stats
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight" alt="Abdelaal's GitHub Stats" />
</p>

📬 **Let's Connect!** 
*   [LinkedIn](https://www.linkedin.com/in/YOUR_LINKEDIN) 
*   [Email](mailto:your.email@example.com)
