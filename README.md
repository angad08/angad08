# Angad Kadam

### 📊 Data Analyst | BI | SQL | Power BI | Python | Process Automation

> _I find patterns in operational and research data, work out where the process breaks, and build something the team can actually use._

📍 Melbourne, VIC, Australia  
📧 [angadkadam08@gmail.com](mailto:angadkadam08@gmail.com) · 📱 +61 405 636 599  
🔗 [LinkedIn](https://linkedin.com/in/angad-kadam-03b606159) · [GitHub](https://github.com/angad08) · [Kaggle](https://kaggle.com/angadk268)

---

## 👤 Profile

Rebuilt a manual Excel-to-Word workflow into a Python-supported automation and reporting pipeline, reducing document preparation time by approximately **~99%** and helping reduce a high-volume operational backlog by approximately **89% in one week**.

Co-authored a published La Trobe research project by turning raw student survey data into analysis-ready datasets, Power BI dashboards, and an applied machine learning workflow that helped faculty explore motivation patterns without relying on raw spreadsheets.

Data Analyst with a Master of Data Science from La Trobe University, currently working across reporting, validation, workflow improvement, and data visibility at the Consulate General of India, Melbourne. I work mainly with SQL, Power BI, Python, PostgreSQL, Excel, and R, with hands-on exposure to Azure ML, AWS RDS, Azure SQL, and Oracle PL/SQL.

My work follows a simple pattern: read the data, understand the workflow, find where the process breaks, and build something the team can actually use.

---

## ⚡ Impact at a Glance

| 🎯 Area | 📈 Result |
|---|---|
| **Workflow automation & reporting** | Reduced document preparation from minutes per record to seconds, approximately **~99% efficiency gain**, by replacing a manual Excel-to-Word workflow with a Python-supported automation and reporting pipeline. |
| **Backlog reduction** | Helped reduce a high-volume operational backlog by approximately **89% in one week**, compared with close to a month of manual work. |
| **High-volume processing** | Processed **108 records in around 16 seconds**. Production runs can handle 1,440-record batches cleanly. |
| **Data validation** | Caught missing fields, duplicate records, formatting issues, and workflow inconsistencies across **150+ operational records reviewed weekly** before they reached processing. |
| **Cross-system audit** | Delivered clean matched output for an ARN audit by reconciling records across disconnected systems under time pressure. |
| **Research analytics** | Co-authored a published La Trobe research paper and built dashboards that helped faculty explore student motivation patterns without relying on raw spreadsheets. |
| **Database redesign** | Reduced report generation time by around **30%** by restructuring flat data into a normalised relational model. |

---

## 💼 Professional Experience

### 🏛️ Consulate General of India, Melbourne  
**Data Analyst, Operations Reporting & Process Improvement** · *Sep 2024 to Present*

I support operational reporting, workflow improvement, and data validation across internal processes.

🔹 **Reduced document preparation from minutes per record to seconds, approximately ~99% efficiency gain**, by building DocuMate, an internal Python-supported automation and reporting pipeline that replaced a manual, spreadsheet-bound workflow.

- Helped reduce a high-volume operational backlog by approximately **89% in one week**, compared with close to a month of manual work.
- Created a repeatable process that combined validation, batch processing, and reporting visibility.

🔹 **Caught missing fields, duplicate records, formatting issues, and record-level changes before processing** by adding validation checks ahead of document generation, instead of finding errors after the fact.

🔹 **Made fragmented workflow data queryable and Power BI-ready** by restructuring it into a normalised PostgreSQL schema with related tables and SQL joins.

🔹 **Surfaced issues before they reached the next processing stage** by validating 150+ operational records each week.

🔹 **Delivered clean matched Excel output under time pressure** for an ARN audit by identifying file numbers as the join key and reconciling data across disconnected source systems.

**Stack:** Python · PostgreSQL · SQL · Power BI · Excel

---

### 🎓 La Trobe University, Melbourne  
**Data Analyst, Research Project** · *Jun 2023 to Jan 2024*

Co-authored a published research paper with six faculty members on student motivation in hybrid teaching environments.

🔹 **Made raw survey data analysis-ready** by cleaning and structuring it in Python and R, supporting exploratory analysis, statistical interpretation, and model development.

🔹 **Distinguished intrinsic and extrinsic motivation patterns** by building SVM classification models in scikit-learn.

- Local `.pkl` inference: **96.81%** accuracy.
- Azure ML REST endpoint: **98.93%** accuracy.
- Audited the gap between local and cloud inference results.

🔹 **Helped faculty explore motivation trends by campus, gender, and teaching mode** without returning to raw spreadsheets through Power BI dashboards built with Power Query and DAX.

🔹 **Gave the research team an interactive way to test motivation predictions** by delivering a Streamlit app.

🔹 **Outcome:** the paper was published, and the dashboards supported faculty interpretation of student motivation patterns across groups and teaching conditions.

**Stack:** Python · R · scikit-learn · Power BI · DAX · Streamlit · Azure ML Studio

---

### 💻 FIS Global, Mumbai  
**Junior Software Engineer** · *Aug 2020 to Mar 2021*

Application support for **ACBS Transaction Server**, a commercial lending and banking transaction platform.

🔹 **Identified recurring performance and throughput issues** by analysing application logs on the platform.

🔹 **Improved processing stability** through configuration and workflow fixes.

🔹 **Traced vendor-escalated issues to internal configuration causes**, reducing escalation back-and-forth.

**Stack:** Log analysis · Application support · Configuration analysis · Banking transaction systems

---

## 🚀 Featured Projects

### 📑 DocuMate · Internal Automation & Reporting Pipeline

🔗 [GitHub Repository](https://github.com/angad08/DocuMate-analytics-pipeline)

> An internal tool that converts a manual document workflow into a faster, validated, and reportable data process.

**🔴 Problem**

Document preparation was handled manually across Excel and Word. Each record needed checking, formatting, validation, and document generation. At operational volumes, this created delays, backlog pressure, and a higher chance of errors entering the workflow.

**🟡 Solution**

Built DocuMate as a Python-supported automation and reporting pipeline:

- Normalised PostgreSQL schema as the structured data layer
- SQL joins to connect related workflow records
- Python orchestration for validation and processing
- Batched Word Mail Merge for high-volume document generation
- Power BI reporting for backlog, processing status, and data quality

**🟢 Impact**

*Direct result of the automation:*

- Reduced document preparation from minutes per record to seconds, approximately **~99% efficiency gain**.
- Processed 108 records in around 16 seconds. Production runs can handle 1,440-record batches cleanly.
- Validation now happens before documents are generated, not after errors are found.

*What that enabled downstream:*

- Helped reduce a high-volume operational backlog by approximately **89% in one week**, compared with close to a month of manual work.
- Remaining records depended mainly on source file availability.
- Workflow data became queryable, reportable, and easier to audit instead of staying trapped in spreadsheets.

**🎯 Outcome**

A manual operational process became a data-driven workflow with validation, automation, and clear reporting, supporting faster processing, cleaner records, and better day-to-day decisions.

**Stack:** Python · PostgreSQL · SQL · Power BI · Excel · Word Mail Merge

---

### 🎓 Hybrid Teaching Motivation Analytics

🔗 [Streamlit App](https://hybmotvnsurvey.streamlit.app/)

> A published La Trobe research project using survey analytics, machine learning, dashboards, and interactive reporting.

**🔴 Problem**

The research team had raw student motivation survey data from a hybrid teaching environment. It needed to be cleaned, analysed, modelled, and presented in a way non-technical faculty could use.

**🟡 Solution**

Built an end-to-end analytics workflow:

- Cleaned and structured raw survey responses
- Ran exploratory analysis to surface motivation patterns
- Built SVM classification models to distinguish intrinsic and extrinsic motivation
- Compared local `.pkl` inference with Azure ML REST endpoint results
- Built Power BI dashboards for faculty-level exploration
- Delivered a Streamlit app for interactive model use

**🟢 Impact**

- Co-authored a published paper with six faculty members.
- Replaced spreadsheet-based review with dashboards faculty could return to.
- Helped faculty explore motivation gaps by campus, gender, and teaching mode.
- Turned raw survey data into a reusable analytics workflow instead of a static research spreadsheet.

**🎯 Outcome**

Raw survey data became a published research output, an interactive dashboard, and a reusable analytics workflow.

**Stack:** Python · R · scikit-learn · Power BI · Streamlit · Azure ML Studio

---

### 🗄️ ServiceMatch · Relational Database Redesign

🔗 [Project Link](https://bit.ly/4ldpA1d)

**🔴 Problem**

Service-matching data was stored in a flat structure. Reports were slow, queries were harder to maintain, and adding new logic meant unnecessary rework.

**🟡 Solution**

Redesigned the data into normalised relational tables with primary and foreign keys, and implemented reporting logic using Oracle PL/SQL and stored procedures.

**🟢 Impact**

- Reduced report generation time by around 30%.
- Made queries more consistent and easier to maintain.
- Created a structure that could take new logic without breaking older reports.

**🎯 Outcome**

A fragile reporting setup became a more dependable relational design that was easier to query, maintain, and extend.

**Stack:** Oracle PL/SQL · SQL · Database Design · Stored Procedures

---

### 📰 News Classification with PyTorch

🔗 [Project Link](https://bit.ly/47chy57)

**🔴 Problem**

Build a multi-class news classifier without relying on pre-trained transformer models.

**🟡 Solution**

Created a custom text-classification pipeline with tokenisation, embeddings, a training loop, and evaluation built from the ground up.

**🟢 Impact**

- Reached 77% accuracy across four news categories.
- Built practical understanding of NLP fundamentals beyond surface-level API use.

**🎯 Outcome**

A hands-on NLP project that strengthened understanding of model training, text preprocessing, and classification workflows.

**Stack:** Python · PyTorch · NLP

---

## 🛠️ Core Skills & Tools

**Technologies:** `SQL` · `PostgreSQL` · `MySQL` · `Oracle PL/SQL` · `Azure SQL` · `Power BI` · `DAX` · `Power Query` · `Python` · `R` · `pandas` · `NumPy` · `scikit-learn` · `PyTorch` · `Azure ML Studio` · `AWS RDS` · `Streamlit` · `Excel` · `Git` · `ODBC` · `DBeaver`

**Competencies:** Data analysis & EDA · BI and dashboard reporting · KPI reporting · Data modelling · Data validation & quality checks · Process improvement · Workflow automation · Cross-system data reconciliation · Stakeholder-facing reporting · Local vs cloud model inference

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
