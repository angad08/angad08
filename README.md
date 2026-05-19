# Angad Kadam

### 📊 Data Analyst | BI Analyst | SQL | Power BI | Python | Data-Driven Automation

> _I turn messy data and broken workflows into reporting, validation, and automation systems people can actually use._

📍 Melbourne, VIC, Australia · Open to relocate  
📧 [angadkadam08@gmail.com](mailto:angadkadam08@gmail.com) · 📱 +61 405 636 599  
🔗 [LinkedIn](https://linkedin.com/in/angad-kadam-03b606159) · [GitHub](https://github.com/angad08) · [Kaggle](https://kaggle.com/angadk268)

---

## 👤 Profile

I like data work that starts with a real problem, not a perfect dataset.

At the Consulate General of India, Melbourne, I designed and deployed **DocuMate**, a Python and PostgreSQL-backed automation and reporting workflow that replaced manual Excel-to-Word document preparation. It reduced per-record preparation from minutes to seconds, delivered around **99% processing efficiency**, and helped clear approximately **88% of a pending operational backlog within one week**.

At La Trobe University, I worked on a published research project examining student motivation in hybrid teaching environments. I turned raw survey responses into cleaned datasets, exploratory analysis, SVM classification models, Power BI dashboards, and a Streamlit app so faculty could explore motivation patterns without repeatedly going back to raw spreadsheets.

That is the common thread in my work: find where the data or process is breaking, structure it properly, and build something useful around it.

---

## ⚡ Impact at a Glance

| 🎯 Area | 📈 Result |
|---|---|
| **Workflow automation & reporting** | Designed and deployed DocuMate, replacing manual Excel-to-Word preparation with a Python-supported automation and reporting workflow. |
| **Processing efficiency** | Reduced document preparation from minutes per record to seconds, delivering around **99% processing efficiency**. |
| **Backlog reduction** | Helped clear approximately **88% of a pending operational backlog within one week**, compared with around one month manually. |
| **Structured reporting source** | Restructured fragmented workflow data into a normalised PostgreSQL model with SQL joins, making records queryable and Power BI-ready. |
| **Data validation** | Added checks for missing fields, duplicate entries, formatting inconsistencies, and record-level changes before processing. |
| **Cross-system reconciliation** | Reconciled disconnected records for an internal audit and delivered clean matched output under tight time pressure. |
| **Research analytics** | Co-authored a published La Trobe research output by combining survey data preparation, exploratory analysis, classification modelling, dashboards, and interpretation support. |
| **Model deployment validation** | Compared **96.81%** local `.pkl` inference accuracy with **98.93%** Azure ML REST endpoint accuracy to check deployment consistency. |
| **Database redesign** | Reduced report generation time by around **30%** by restructuring flat data into a normalised relational model. |

---

## 🧠 How I Think About Data

I do not see data work as only building dashboards or writing queries. Most useful analytics work starts earlier than that.

- Where is the workflow breaking?
- Which fields are unreliable?
- What needs to be validated before reporting?
- What should be automated instead of repeated manually?
- What does the final user need to see, decide, or act on?

That is why my projects often sit across **SQL, Power BI, Python, validation logic, automation, and applied analytics**. The point is not just the tool. The point is whether the work makes the process clearer, faster, and easier to trust.

---

## 💼 Professional Experience

### 🏛️ Consulate General of India, Melbourne  
**Data Analyst, Administrative and Consular Operations** · *Sep 2024 to Present*

Internal data, automation, and reporting role focused on improving high-volume workflows through structured data, validation checks, and Power BI-ready reporting.

🔹 **Reduced document preparation from minutes per record to seconds** by designing and deploying DocuMate, a Python and PostgreSQL-backed automation and reporting workflow that replaced manual Excel-to-Word preparation.

- Delivered around **99% processing efficiency** across batch document preparation.
- Helped clear approximately **88% of a pending operational backlog within one week**, compared with around one month manually.
- Deployed the solution into live internal use, combining validation, batch processing, and reporting visibility.

🔹 **Improved process reliability and reduced manual review effort** by translating workflow pain points from internal users into structured data, validation, and automation logic.

🔹 **Made scattered workflow data queryable and Power BI-ready** by restructuring fragmented records into a normalised PostgreSQL schema with related tables and SQL joins.

🔹 **Reduced repeated review cycles** by designing validation and change-flagging logic to catch missing fields, duplicate entries, formatting inconsistencies, and updated record details before processing.

🔹 **Delivered audit-ready cross-system output under time pressure** by identifying a reliable join key, reconciling disconnected records, and producing clean matched Excel outputs for review.

**Stack:** Python · PostgreSQL · SQL · Power BI · Excel

---

### 🎓 La Trobe University, Melbourne  
**Data Analyst, Research Project** · *Jun 2023 to Jan 2024*

Faculty-supervised research project examining intrinsic and extrinsic motivation in hybrid teaching environments using survey data, classification modelling, and BI dashboards.

🔹 **Converted raw survey responses into research-ready evidence** by cleaning and structuring inconsistent Excel data in Python and R, then running exploratory analysis to surface early motivation patterns.

🔹 **Distinguished intrinsic and extrinsic motivation patterns** by building and validating SVM classification models in scikit-learn.

- Local `.pkl` inference: **96.81%** accuracy.
- Azure ML REST endpoint inference: **98.93%** accuracy.
- Audited the difference between local and cloud inference results to check deployment behaviour.

🔹 **Enabled faculty self-serve exploration of motivation patterns** by building Power BI dashboards with Power Query and DAX, covering gender, campus, and teaching mode.

🔹 **Made the model easier to use** by delivering a Streamlit app for interactive motivation prediction inputs.

🔹 **Contributed to a published research output** by translating survey data into model-backed insights that supported clearer interpretation of motivation, engagement, and learning-mode patterns.

**Stack:** Python · R · scikit-learn · Power BI · DAX · Streamlit · Azure ML Studio

---

### 💻 FIS Global, Mumbai  
**Junior Software Engineer** · *Aug 2020 to Mar 2021*

Junior software engineering role supporting **ACBS Transaction Server**, a commercial lending and banking transaction processing platform used by financial institutions.

🔹 **Identified recurring performance and throughput issues** by analysing transaction logs and recurring incidents on the platform.

🔹 **Supported processing stability** by working on workflow and configuration fixes.

🔹 **Reduced unnecessary external dependency** by tracing vendor-escalated issues to internal configuration causes.

**Stack:** Log analysis · Application support · Configuration analysis · Banking transaction systems

---

## 🚀 Featured Projects

### 📑 DocuMate · Internal Automation & Reporting Pipeline

🔗 [GitHub Repository](https://github.com/angad08/DocuMate-analytics-pipeline)

> A live internal workflow improvement project where automation, validation, structured data, and reporting came together.

**🔴 Problem**

The original workflow relied on scattered spreadsheets and manual Excel-to-Word document preparation. Each record needed checking, formatting, validation, and generation. At high volume, this created delays, backlog pressure, and repeated manual review.

**🟡 What I Built**

I expanded the original automation idea into a structured data and reporting workflow:

- Python orchestration for validation and batch processing
- PostgreSQL-backed data model instead of scattered spreadsheet-only tracking
- SQL joins to connect related workflow records
- Batched Word Mail Merge for high-volume generation
- Validation checks before output generation
- Power BI-ready tracking for backlog, processing status, and data quality

**🟢 Impact**

- Reduced preparation time from minutes per record to seconds.
- Delivered around **99% processing efficiency** in document preparation.
- Helped clear approximately **88% of a pending operational backlog within one week**.
- Processed 108 records in around 16 seconds, with production runs supporting 1,440-record batches.
- Moved workflow visibility from scattered spreadsheets into a queryable and reportable structure.

**🎯 Outcome**

DocuMate turned a repetitive manual process into a data-driven workflow with validation, automation, and reporting visibility. It is the clearest example of how I approach analytics work: understand the process first, structure the data, then build the tool.

**Stack:** Python · PostgreSQL · SQL · Power BI · Excel · Word Mail Merge

---

### 🎓 Hybrid Teaching Motivation Analytics

🔗 [Streamlit App](https://hybmotvnsurvey.streamlit.app/)

> A published La Trobe research project where survey data became dashboards, models, and an interactive analytics workflow.

**🔴 Problem**

The research team had raw student motivation survey data from a hybrid teaching environment. The data needed to be cleaned, analysed, modelled, and presented in a way that non-technical faculty could use.

**🟡 What I Built**

- Cleaned and structured raw survey responses in Python and R
- Ran exploratory analysis to surface motivation patterns
- Built SVM classification models to distinguish intrinsic and extrinsic motivation
- Compared local `.pkl` inference with Azure ML REST endpoint inference
- Built Power BI dashboards for faculty-level exploration
- Delivered a Streamlit app for interactive model use

**🟢 Impact**

- Contributed to a published research output with six faculty members.
- Replaced repeated spreadsheet review with dashboards faculty could return to.
- Helped faculty explore motivation patterns by gender, campus, and teaching mode.
- Validated model behaviour across local and cloud inference paths.
- Turned raw survey data into a reusable analytics workflow.

**🎯 Outcome**

The project connected research analytics, BI reporting, and applied machine learning in one workflow. It showed how analysis can move beyond a static spreadsheet and become something stakeholders can explore.

**Stack:** Python · R · scikit-learn · Power BI · Streamlit · Azure ML Studio

---

### 🗄️ ServiceMatch · Relational Database Design for Reporting

🔗 [Project Link](https://bit.ly/4ldpA1d)

**🔴 Problem**

Service-matching data was stored in a flat structure. Reports were slow, queries were harder to maintain, and adding new logic meant unnecessary rework.

**🟡 What I Built**

Redesigned the data into normalised relational tables with primary and foreign keys, then implemented reporting logic using Oracle PL/SQL and stored procedures.

**🟢 Impact**

- Reduced report generation time by around 30%.
- Improved data integrity and query consistency.
- Created a reporting structure that could support new logic without breaking older reports.

**🎯 Outcome**

A fragile reporting setup became a more dependable relational design that was easier to query, maintain, and extend.

**Stack:** Oracle PL/SQL · SQL · Database Design · Stored Procedures

---

### 📰 News Classification with PyTorch

🔗 [Project Link](https://bit.ly/47chy57)

**🔴 Problem**

Build a multi-class news classifier without relying on pre-trained transformer models.

**🟡 What I Built**

Created a custom text-classification pipeline with tokenisation, embeddings, a training loop, and evaluation built from the ground up.

**🟢 Impact**

- Reached 77% accuracy across four news categories.
- Built practical understanding of NLP fundamentals beyond surface-level API use.

**🎯 Outcome**

A hands-on NLP project that strengthened understanding of model training, text preprocessing, and classification workflows.

**Stack:** Python · PyTorch · NLP

---

## 🛠️ Core Skills

**Technologies:** SQL · Power BI · DAX · Power Query · Excel · Python · R · PostgreSQL · MySQL · Oracle PL/SQL · Azure SQL · AWS RDS · Supabase · pandas · NumPy · scikit-learn · Azure ML Studio · Streamlit · PyTorch · Git · GitHub · ODBC · DBeaver

**Competencies:** data cleaning · data validation · exploratory data analysis · KPI analysis · analytical reporting · dashboard design · data modelling · workflow automation · process improvement · cross-system data reconciliation · hypothesis testing · classification · regression · SVM · model evaluation · REST API inference · insight generation · decision support

---

## 🎓 Education

**Master of Data Science**  
La Trobe University, Melbourne · *Feb 2022 to Dec 2023*  
Focus: Business Intelligence, Predictive Analytics, Statistical Modelling

**Bachelor of Engineering in Information Technology**  
PVPPCOE, Mumbai · *Aug 2014 to Aug 2019*

---

## 📜 Certifications

- Power BI Data Modeling with DAX · LinkedIn Learning
- Power BI Data Methods · PMI
- Exploratory Data Analysis with Python and Pandas · Coursera
- Building Deep Learning Applications with Keras and PyTorch · LinkedIn Learning
