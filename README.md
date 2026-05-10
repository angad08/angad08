# Angad Kadam

### 📊 Data Analyst | BI | SQL | Power BI | Python

> _Analytical by instinct. Data Analyst with a Master's in Data Science. I find patterns in data and the processes around it, and surface insights for decisions. Looking for roles where that thinking is the job._

📍 Melbourne, VIC, Australia
📧 [angadkadam08@gmail.com](mailto:angadkadam08@gmail.com) · 📱 +61 405 636 599
🔗 [LinkedIn](https://linkedin.com/in/angad-kadam-03b606159) · [GitHub](https://github.com/angad08) · [Kaggle](https://kaggle.com/angadk268)

---

## 👤 Profile

Master of Data Science from La Trobe University. Currently a Data Analyst at the Consulate General of India, Melbourne.

I work mainly in **SQL, Power BI, Python, R, and PostgreSQL**, with hands-on exposure to Azure ML, AWS RDS, and Oracle PL/SQL.

Most of my real impact follows one pattern. **Read the data. Find what it's saying. Decide what's needed. Build something the team will use.**

---

## ⚡ Impact at a Glance

| 🎯 What | 📈 Result |
|---|---|
| **DocuMate automation** | **~99% efficiency gain.** Document preparation went from minutes per record to seconds across the batch. |
| **Downstream effect** | Once DocuMate was live, the **Dispatch team cleared a 96% backlog in one week**. That same volume took close to a month before. |
| **Throughput** | 108 records in ~16 seconds. Production runs handle 1,440-record batches cleanly. |
| **Consular validation** | 150+ records reviewed weekly. Issues caught before processing, not after. |
| **Cross-system audit** | Reconciled disconnected systems for an ARN audit. Delivered clean output under time pressure. |
| **Hybrid Teaching research** | Co-authored published paper. Faculty now use dashboards instead of spreadsheets. |
| **Database redesign** | Flat data restructured into normalised relational models. Reporting time dropped ~30%. |

---

## 🛠️ Tech Stack

**Analytics & BI** · `SQL` · `Power BI` · `DAX` · `Power Query` · `Excel` · `Data Modelling` · `EDA`

**Programming & Automation** · `Python` · `R` · `pandas` · `NumPy` · `Streamlit`

**Databases & Cloud** · `PostgreSQL` · `MySQL` · `Oracle PL/SQL` · `Azure SQL` · `AWS RDS` · `ODBC`

**Machine Learning** · `scikit-learn` · `SVM` · `PyTorch` · `Azure ML Studio` · `REST API Inference`

**Tools** · `Git` · `GitHub` · `VS Code` · `DBeaver`

---

## 💼 Professional Experience

### 🏛️ Consulate General of India, Melbourne
**Data Analyst, Administrative & Consular Operations** · *Sep 2024 to Present*

I support consular operations and build internal tools that reduce manual work and improve visibility across the workflow.

🔹 **Built DocuMate**, an internal Python automation tool that replaced a manual Excel-to-Word document workflow.
- **~99% efficiency gain** on document preparation. Minutes per record collapsed into seconds across the batch.
- Downstream: the **Dispatch team cleared a 96% backlog in one week**. Same workload took close to a month before.

🔹 **Designed change-flagging logic** so officers spot updated applicant details without re-reading full application histories.

🔹 **Restructured fragmented workflow data** into a normalised PostgreSQL schema with related tables and SQL joins. Records are now queryable and connected to Power BI reporting.

🔹 **Validate 150+ applicant records weekly.** Catch missing fields, duplicates, and formatting issues before they reach processing.

🔹 **Reconciled cross-system records** for a first-passport ARN audit. Identified file numbers from internal records as the join key, matched across systems, and delivered a clean Excel output (name, file number, address, parents' passport number, ARN) under tight time pressure.

**Stack:** Python · PostgreSQL · SQL · Power BI · Excel

---

### 🎓 La Trobe University, Melbourne
**Data Analyst, Research Project** · *Jun 2023 to Jan 2024*

Co-authored a published research paper with six faculty members on student motivation in hybrid teaching environments.

🔹 **Cleaned and structured** raw Excel survey data using Python and R, ready for analysis.

🔹 **Built classification models** in scikit-learn (SVM) to distinguish intrinsic from extrinsic motivation patterns.
- Local `.pkl` inference: **96.81%** accuracy. Azure ML REST endpoint: **98.93%**. Audited the gap between the two.

🔹 **Built Power BI dashboards** using DAX and Power Query so faculty could explore motivation trends by campus, gender, and teaching mode without going back to spreadsheets.

🔹 **Delivered a Streamlit app** for the research team to use the model interactively.

🔹 **Outcomes:** the paper was published. Faculty now use the dashboards to spot motivation gaps across student groups. Findings linked hybrid teaching to a measurable improvement in engagement indicators (~27%).

**Stack:** Python · R · scikit-learn · Power BI · DAX · Streamlit · Azure ML Studio

---

### 💻 FIS Global, Mumbai
**Junior Software Engineer** · *Aug 2020 to Mar 2021*

Application support for an ATS platform.

🔹 Analysed application logs to identify recurring performance and throughput problems.

🔹 Worked on configuration and workflow fixes that improved availability and processing throughput.

🔹 Investigated issues that had been escalated to external vendors and resolved internal configuration causes.

**Stack:** Log analysis · Application support · Configuration analysis

---

## 🚀 Featured Projects

### 📑 DocuMate · Internal Automation & Reporting Pipeline

🔗 [GitHub Repository](https://github.com/angad08/DocuMate-analytics-pipeline)

> Internal tool I built at the Consulate to replace a manual document preparation workflow. Real users. Real backlog. Real outcome.

**🔴 Problem**

Each consular record needed manual preparation across Excel and Word. Format, check, validate, generate document. At consular volumes, the Dispatch team was carrying weeks of backlog. Records sat waiting. Errors slipped through.

**🟡 Solution**

Started as a Python script reading from Excel into Word templates. Evolved across versions into a structured pipeline.

- Normalised PostgreSQL schema as the data source
- SQL joins to pull related records
- Python orchestration layer
- Batched Word Mail Merge for high-volume runs
- Power BI reporting on the same data

**🟢 Impact**

*Direct result of automation:*
- **~99% efficiency gain** on document preparation. Minutes per record turned into seconds across the batch.
- 108 records process in ~16 seconds. Production batches of 1,440 records run cleanly in the same architecture.
- Validation now happens **before** documents are generated, not after errors are found.

*What that enabled downstream:*
- **Dispatch team cleared a 96% backlog in one week.** That same workload had been taking close to a month.
- Workflow data is now queryable and reportable instead of trapped in spreadsheets.

**🎯 Outcome**

A manual operational process became a data-driven workflow with reporting visibility. Officers trust the output. Dispatch caught up on a backlog that used to feel permanent.

**Stack:** Python · PostgreSQL · SQL · Power BI · Excel · Word Mail Merge

---

### 🎓 Hybrid Teaching Motivation Analytics

🔗 [Streamlit App](https://hybmotvnsurvey.streamlit.app/)

> Co-authored research project at La Trobe. Six faculty members. One published paper.

**🔴 Problem**

The research team had raw survey data on student motivation in hybrid teaching. Six faculty members. No clear way to clean it, model it, or present findings to a non-technical audience.

**🟡 Solution**

End-to-end analytics workflow.

- Cleaned and structured the raw survey responses
- Ran exploratory analysis to surface motivation patterns
- Built SVM classification models to separate intrinsic from extrinsic motivation
- Compared local `.pkl` inference (96.81%) with Azure ML REST endpoint (98.93%) and audited the gap
- Built Power BI dashboards for the research team
- Delivered a Streamlit app for interactive use

**🟢 Impact**

- **Paper published** with six faculty members as co-authors.
- Faculty now use the dashboards to spot motivation gaps by campus, gender, and teaching mode.
- Spreadsheet-based review replaced with a dashboard the team can return to.
- Findings supported the conclusion that hybrid teaching improved engagement indicators (~27%).

**🎯 Outcome**

Raw survey data became a published research output and an ongoing tool the faculty actually use. The analysis didn't sit in a folder.

**Stack:** Python · R · scikit-learn · Power BI · Streamlit · Azure ML Studio

---

### 🗄️ ServiceMatch · Relational Database Redesign

🔗 [Project Link](https://bit.ly/4ldpA1d)

**🔴 Problem**

Service-matching data sat in a flat structure. Reports were slow. Queries were unreliable. Adding new logic meant rewriting from scratch.

**🟡 Solution**

Normalised the schema. Designed proper relational tables with primary and foreign keys. Implemented in Oracle PL/SQL with stored procedures.

**🟢 Impact**

- Report generation time dropped by ~30%.
- Queries became consistent and predictable.
- The schema can absorb new logic without breaking older reports.

**🎯 Outcome**

A reporting layer that the team can rely on, instead of one they have to babysit.

**Stack:** Oracle PL/SQL · SQL · Database Design · Stored Procedures

---

### 📰 News Classification with PyTorch

🔗 [Project Link](https://bit.ly/47chy57)

**🔴 Problem**

Build a multi-class news classifier without leaning on pre-trained transformer models.

**🟡 Solution**

Custom text-processing pipeline. Tokenisation, embeddings, training loop, evaluation. Built from the ground up.

**🟢 Impact**

- 77% accuracy across four news categories.
- Working understanding of every layer in the pipeline, beyond surface-level API use.

**🎯 Outcome**

Hands-on grounding in NLP fundamentals. The kind of project where you build the model, you don't just call one.

**Stack:** Python · PyTorch · NLP

---

## 🎓 Education

**Master of Data Science**
La Trobe University, Melbourne · *Feb 2022 to Dec 2023*
Focus: BI, predictive analytics, statistical modelling, data visualisation, ML, research analytics.

**Bachelor of Engineering, Information Technology**
PVPPCOE, Mumbai · *Aug 2014 to Aug 2019*

---

## 📜 Certifications

- Power BI Data Modeling with DAX · LinkedIn Learning
- Power BI Data Methods · PMI
- Exploratory Data Analysis with Python and Pandas · Coursera
- Building Deep Learning Applications with Keras and PyTorch · LinkedIn Learning
