# Angad Kadam

### 📊 Data Analyst | BI | SQL | Power BI | Python | Process Automation

> _Analytical by instinct. I find patterns in operational and research data, understand the process around them, and turn that into something the team can actually use._

📍 Melbourne, VIC, Australia  
📧 [angadkadam08@gmail.com](mailto:angadkadam08@gmail.com) · 📱 +61 405 636 599  
🔗 [LinkedIn](https://linkedin.com/in/angad-kadam-03b606159) · [GitHub](https://github.com/angad08) · [Kaggle](https://kaggle.com/angadk268)

---

## 👤 Profile

Master of Data Science from La Trobe University. Currently working across data, reporting, validation, and operational improvement at the Consulate General of India, Melbourne.

My strongest work sits where data meets real workflow problems: cleaning messy records, finding the process gap, building the reporting layer, and creating tools people can actually use.

I work mainly with **SQL, Power BI, Python, PostgreSQL, Excel, and R**, with hands-on exposure to Azure ML, AWS RDS, Azure SQL, and Oracle PL/SQL.

---

## ⚡ Impact at a Glance

| 🎯 Area | 📈 Result |
|---|---|
| **DocuMate automation** | Rebuilt a manual Excel-to-Word consular workflow into a Python-supported document automation and reporting process. |
| **Processing efficiency** | Reduced document preparation from minutes per record to seconds across batch processing, achieving approximately **~99% efficiency gain**. |
| **Dispatch backlog support** | Helped the Dispatch team clear approximately **480 of 540 passport dispatch cases in one week**, around **89% of the backlog**. Remaining cases depended mainly on file availability. |
| **High-volume processing** | Processed 108 records in around 16 seconds. Production runs can handle 1,440-record batches cleanly. |
| **Data validation** | Reviewed 150+ applicant records weekly and caught missing fields, duplicate records, formatting issues, and workflow inconsistencies before processing. |
| **Cross-system audit** | Reconciled disconnected records for an ARN audit and delivered clean matched output under time pressure. |
| **Hybrid Teaching research** | Co-authored a published La Trobe research paper and built dashboards that helped faculty explore student motivation patterns without relying on raw spreadsheets. |
| **Database redesign** | Restructured flat data into normalised relational models, making queries more consistent and reducing report generation time by around 30%. |

---

## 💼 Professional Experience

### 🏛️ Consulate General of India, Melbourne  
**Data Analyst, Administrative & Consular Operations** · *Sep 2024 to Present*

I support consular operations by improving how applicant records, workflow data, validation checks, and reporting outputs are handled across the team.

🔹 **Built DocuMate**, an internal Python-supported automation and reporting pipeline that converted a manual, spreadsheet-bound document workflow into a validated and reportable data process.

- Reduced document preparation from minutes per record to seconds across batch processing.
- Achieved approximately **~99% efficiency gain** in document preparation.
- Helped the Dispatch team clear approximately **480 of 540 passport dispatch cases in one week**, around **89% of the backlog**. Remaining cases depended mainly on file availability.

🔹 **Improved data quality before processing** by adding checks for missing fields, duplicate records, formatting issues, and applicant detail changes.

🔹 **Restructured fragmented workflow data** into a normalised PostgreSQL schema with related tables and SQL joins, making records queryable and ready for Power BI reporting.

🔹 **Validated 150+ applicant records weekly**, helping officers catch issues before they reached processing or dispatch.

🔹 **Reconciled cross-system records** for a first-passport ARN audit by identifying file numbers as the join key, matching data across disconnected sources, and delivering clean Excel output under time pressure.

**Stack:** Python · PostgreSQL · SQL · Power BI · Excel

---

### 🎓 La Trobe University, Melbourne  
**Data Analyst, Research Project** · *Jun 2023 to Jan 2024*

Co-authored a published research paper with six faculty members on student motivation in hybrid teaching environments.

🔹 **Converted raw survey data into analysis-ready datasets** using Python and R, supporting exploratory analysis, statistical interpretation, and model development.

🔹 **Built classification models** in scikit-learn to distinguish intrinsic and extrinsic motivation patterns.

- Local `.pkl` inference: **96.81%** accuracy.
- Azure ML REST endpoint: **98.93%** accuracy.
- Audited the gap between local and Azure inference results.

🔹 **Built Power BI dashboards** using Power Query and DAX so faculty could explore motivation trends by campus, gender, and teaching mode without going back to raw spreadsheets.

🔹 **Delivered a Streamlit app** that allowed the research team to interact with the model and test motivation prediction inputs.

🔹 **Outcome:** the paper was published, and the dashboards helped faculty interpret student motivation patterns across different groups and teaching conditions.

**Stack:** Python · R · scikit-learn · Power BI · DAX · Streamlit · Azure ML Studio

---

### 💻 FIS Global, Mumbai  
**Junior Software Engineer** · *Aug 2020 to Mar 2021*

Worked in application support for **ACBS Transaction Server**, a commercial lending and banking transaction platform.

🔹 Analysed application logs to identify recurring performance and throughput issues.

🔹 Worked on configuration and workflow fixes that improved processing stability.

🔹 Investigated vendor-escalated issues and identified internal configuration causes.

**Stack:** Log analysis · Application support · Configuration analysis · Banking transaction systems

---

## 🚀 Featured Projects

### 📑 DocuMate · Internal Automation & Reporting Pipeline

🔗 [GitHub Repository](https://github.com/angad08/DocuMate-analytics-pipeline)

> Internal tool built to convert a manual consular document workflow into a faster, validated, and reportable data process.

**🔴 Problem**

Document preparation was handled manually across Excel and Word. Each record required checking, formatting, validation, and document generation. At consular volumes, this created delays, backlog pressure, and a higher chance of errors entering the workflow.

**🟡 Solution**

Built DocuMate as a Python-supported automation and reporting pipeline.

- Normalised PostgreSQL schema as the structured data layer
- SQL joins to connect related applicant and workflow records
- Python orchestration for validation and processing
- Batched Word Mail Merge for high-volume document generation
- Power BI reporting for backlog, processing status, and data quality visibility

**🟢 Impact**

*Direct result of automation:*

- Reduced document preparation from minutes per record to seconds across batch processing.
- Achieved approximately **~99% efficiency gain** in document preparation.
- Processed 108 records in around 16 seconds.
- Production runs can handle 1,440-record batches cleanly.
- Validation now happens before documents are generated, not after errors are found.

*What that enabled downstream:*

- Helped the Dispatch team clear approximately **480 of 540 passport dispatch cases in one week**, around **89% of the backlog**.
- Remaining cases depended mainly on file availability.
- Workflow data became queryable, reportable, and easier to audit instead of staying trapped in spreadsheets.

**🎯 Outcome**

A manual operational process became a data-driven workflow with validation, automation, and reporting visibility. The work supported faster processing, cleaner records, and better day-to-day operational decisions.

**Stack:** Python · PostgreSQL · SQL · Power BI · Excel · Word Mail Merge

---

### 🎓 Hybrid Teaching Motivation Analytics

🔗 [Streamlit App](https://hybmotvnsurvey.streamlit.app/)

> Published La Trobe research project using survey analytics, machine learning, dashboards, and interactive reporting.

**🔴 Problem**

The research team had raw student motivation survey data from a hybrid teaching environment. The data needed to be cleaned, analysed, modelled, and presented in a way that non-technical faculty members could use.

**🟡 Solution**

Built an end-to-end analytics workflow.

- Cleaned and structured raw survey responses
- Ran exploratory analysis to surface motivation patterns
- Built SVM classification models to distinguish intrinsic and extrinsic motivation
- Compared local `.pkl` inference with Azure ML REST endpoint results
- Built Power BI dashboards for faculty-level exploration
- Delivered a Streamlit app for interactive model use

**🟢 Impact**

- Co-authored a published paper with six faculty members.
- Replaced spreadsheet-based review with dashboards that faculty could return to.
- Helped faculty explore motivation gaps by campus, gender, and teaching mode.
- Turned raw survey data into a reusable analytics workflow instead of a static research spreadsheet.

**🎯 Outcome**

Raw survey data became a published research output, an interactive dashboard, and a reusable analytics workflow.

**Stack:** Python · R · scikit-learn · Power BI · Streamlit · Azure ML Studio

---

### 🗄️ ServiceMatch · Relational Database Redesign

🔗 [Project Link](https://bit.ly/4ldpA1d)

**🔴 Problem**

Service-matching data was stored in a flat structure. Reports were slow, queries were harder to maintain, and adding new logic required unnecessary rework.

**🟡 Solution**

Redesigned the data structure into normalised relational tables with primary and foreign keys. Implemented reporting logic using Oracle PL/SQL and stored procedures.

**🟢 Impact**

- Reduced report generation time by around 30%.
- Made queries more consistent and easier to maintain.
- Created a structure that could support new logic without breaking older reports.

**🎯 Outcome**

A fragile reporting setup became a more reliable relational database design that was easier to query, maintain, and extend.

**Stack:** Oracle PL/SQL · SQL · Database Design · Stored Procedures

---

### 📰 News Classification with PyTorch

🔗 [Project Link](https://bit.ly/47chy57)

**🔴 Problem**

Build a multi-class news classifier without relying on pre-trained transformer models.

**🟡 Solution**

Created a custom text-classification pipeline with tokenisation, embeddings, training loop, and evaluation built from the ground up.

**🟢 Impact**

- Achieved 77% accuracy across four news categories.
- Built practical understanding of NLP fundamentals beyond surface-level API use.

**🎯 Outcome**

A hands-on NLP project that strengthened understanding of model training, text preprocessing, and classification workflows.

**Stack:** Python · PyTorch · NLP

---

## 🛠️ Core Skills & Tools

**Data Analysis & BI** · `SQL` · `Power BI` · `DAX` · `Power Query` · `Excel` · `Data Modelling` · `EDA` · `KPI Reporting`

**Programming & Automation** · `Python` · `R` · `pandas` · `NumPy` · `Streamlit`

**Databases & Cloud Exposure** · `PostgreSQL` · `MySQL` · `Oracle PL/SQL` · `Azure SQL` · `AWS RDS` · `ODBC`

**Machine Learning & Applied Analytics** · `scikit-learn` · `SVM` · `PyTorch` · `Azure ML Studio` · `REST API Inference`

**Tools** · `Git` · `GitHub` · `VS Code` · `DBeaver`

---

## 🎓 Education

**Master of Data Science**  
La Trobe University, Melbourne · *Feb 2022 to Dec 2023*  
Focus: BI, predictive analytics, statistical modelling, data visualisation, machine learning, and research analytics.

**Bachelor of Engineering, Information Technology**  
PVPPCOE, Mumbai · *Aug 2014 to Aug 2019*

---

## 📜 Certifications

- Power BI Data Modeling with DAX · LinkedIn Learning
- Power BI Data Methods · PMI
- Exploratory Data Analysis with Python and Pandas · Coursera
- Building Deep Learning Applications with Keras and PyTorch · LinkedIn Learning
