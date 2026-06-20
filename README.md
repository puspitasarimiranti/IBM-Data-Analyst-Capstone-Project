# 📊 Technology Skill & Market Trend Analytics Dashboard
### End-to-End Data Analysis Capstone Project for IBM Data Analyst Professional Certificate

This repository contains the complete end-to-end data pipeline, statistical analysis, and interactive business intelligence dashboard designed to track global technology skill demands, developer demographics, and emerging software trends.

---

## 🌟 Project Overview (STAR Framework)

*   **Situation:** A global IT and Business Services firm needs to identify emerging technology sectors and upcoming skill requirements to keep its engineering teams competitive and optimize corporate training programs.
*   **Task:** My objective was to simulate the role of a Lead Data Analyst tasked with collecting global tech market data from fragmented web sources, cleaning unstructured response sets, conducting deep exploratory analysis, and establishing a centralized visual dashboard tracking market demand metrics.
*   **Action:** 
    *   **Data Sourcing:** Engineered Python web scraping routines (`BeautifulSoup`) and executed REST API queries to collect unstructured compensation and job data.
    *   **Database & ETL:** Loaded a subset of the [Stack Overflow Annual Developer Survey](https://survey.stackoverflow.co/) data (containing ~4,900 rows across 62 variables under an ODbL License) into an SQL relational database, utilizing SQL queries and `Pandas` to load structured segments into DataFrames.
    *   **Data Wrangling:** Implemented an automated profiling pipeline to isolate missing data fields, drop duplicate entries, handle outliers via mathematical statistics, and normalize disparate string text.
    *   **Analysis & Dashboards:** Conducted descriptive analytics to isolate top programming languages and localized databases. Programmed custom maps using `Folium` and engineered interactive monitoring interfaces using **IBM Cognos Analytics** and **Google Looker Studio**.
*   **Result:** Developed an interactive, production-ready BI dashboard architecture that consolidated multi-channel survey results into actionable trend metrics. The final deliverables highlighted top programming languages, prioritized fast-growing cloud/database architectures, and mapped precise engineer geographic concentrations to guide regional staffing strategy.

---

## ⚙️ Tech Stack & Tools
*   **Languages & Frameworks:** Python v3.12.2, SQL (DDL/DML)
*   **Data Infrastructure:** Relational SQL Databases, IBM Cloud Db2
*   **Data Analysis & ETL:** Pandas, NumPy
*   **Visualization Libraries:** Matplotlib, Seaborn, Folium, Plotly
*   **Business Intelligence Platforms:** IBM Cognos Analytics, Google Looker Studio

---

## 📁 Analytical Methodology & Deliverables

### 🔹 Step 1: Data Collection & Sourcing
*   **API Ingestion:** Developed programmatic retrieval scripts to interface with external live web endpoints and parse technical JSON payloads.
*   **Web Scraping:** Constructed HTML parsers utilizing Python `requests` and `BeautifulSoup` to safely extract raw structural tables from target online portals.

### 🔹 Step 2: Data Wrangling & Pipeline Preparation
*   **Data Auditing:** Structured a systematic data cleaning routine to flag, record, and drop duplicated candidate profiles.
*   **Imputation Strategies:** Isolated empty metadata attributes, applying descriptive statistical metrics to accurately replace null values without skewing distribution shapes.
*   **Normalization:** Normalized structural database boundaries to ensure downstream analytical operations ran with absolute precision.

### 🔹 Step 3: Exploratory Data Analysis (EDA)
*   **Statistical Distribution:** Reviewed salary profiles using frequency tables and visual indicators to understand worldwide developer pay models.
*   **Outlier Treatment:** Applied Interquartile Range (IQR) strategies to spot anomalous entries and filter skewed compensation data.
*   **Demographic Segmentation:** Generated correlation models evaluating geographic, educational background, and age groupings against top operational fields.

### 🔹 Step 4: Data Visualization & Reporting
*   **Composition & Relationships:** Rendered clear bubble plots, scatter graphs, and pie models to dissect software tool market share metrics.
*   **Geospatial Analysis:** Leveraged `Folium` to plot geographical concentration graphs, defining regional talent pockets globally.

### 🔹 Step 5: Interactive BI Dashboard Construction
*   Developed dynamic executive visibility tools within **IBM Cognos Analytics**. The dashboard isolates current technology use parameters, upcoming future tech initiatives, and key stakeholder metrics.

---

## 📈 Key Insights & Dashboard Preview

*   **Insight 1:** Python and JavaScript continue to drive contemporary industry workflows, showing a strong correlation with web development and automated scripting frameworks.
*   **Insight 2:** PostgreSQL emerged as a primary target technology sector, marking a distinct corporate migration trend away from traditional legacy relational backends.

<img width="1123" height="477" alt="Screenshot 2026-06-20 at 11 11 02" src="https://github.com/user-attachments/assets/fc2b0883-6e9f-4c0c-86d5-2c0bd0cf84bb" />
<img width="1119" height="497" alt="Screenshot 2026-06-20 at 11 10 54" src="https://github.com/user-attachments/assets/d1b83992-2375-4534-8bb2-77d380721072" />

*Caption: The technical trends and developer demographic analytics matrix*

---

## 📜 Dataset Reference & License
The foundational data utilized for this deployment was derived from the [Stack Overflow Developer Survey](https://survey.stackoverflow.co/), open-sourced under the **Open Database License (ODbL)**. 

*Note: For performance optimizations across local execution runtimes, this repository utilizes a randomized structural subset representing roughly 10% of the primary multi-row survey database.*
