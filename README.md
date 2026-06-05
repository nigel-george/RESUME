# Hi, I'm Nigel George 👋 

### Analytical Engineer | Data Analyst | Python & SQL Specialist
📍 Based in Toronto, ON (Open to Remote, Hybrid, & Relocation across Canada)  
🇨🇦 Canadian Permanent Resident (PR) | 🚗 Valid Canadian Driving Licence

I am a data professional with **5 years of backend engineering experience**, now specializing in **Data Analytics and Analytics Engineering**. I bridge the gap between core software engineering and analytical depth—turning messy, large-scale production data into high-performance data warehouses and actionable business intelligence.

---

### 🛠️ Technical Arsenal

- **Data & Analytics:** SQL (Advanced), PostgreSQL, dbt Core, Star Schema Design, Dimensional Modeling, ETL/ELT Pipelines, Data Warehousing, Power BI, Cohort Analysis
- **Languages & Frameworks:** Python (Pandas, NumPy, Flask, Django), Advanced SQL, JavaScript, Core PHP
- **Tools & Platforms:** Git, GitHub, Docker, DBeaver, pgAdmin, VS Code, Postman, Linux
- **Methodologies:** Data Quality Validation (`pytest`), Query Optimization (`EXPLAIN ANALYZE`), Agile/Scrum, Stakeholder Reporting

---

### 🚀 Featured Data Engineering & Analytics Projects

#### 📈 [Canadian Financial Analytics Platform](https://github.com/nigel-george/financial_sql_advanced)
*An end-to-end financial data warehouse simulating a production-grade Canadian consumer finance platform.*
- **Scale & Tech:** Python | PostgreSQL | Advanced SQL | Star Schema | Power BI | **2.3M+ Rows**
- **Architecture:** Engineered a complete star schema (`fact_transactions`, `dim_customer`, `dim_date`, `dim_category`) with range partitioning and targeted B-Tree indexing, slashing raw table scan times from 12 seconds down to **sub-2-second responses**.
- **Analytics Depth:** Built 8 business modules spanning customer lifetime value, cohort retention matrices, and FP&A variance models. Developed a fraud detection engine using `LAG() OVER (PARTITION BY)` to pinpoint velocity attacks and exact-match duplicate transactions.

#### 🍱 [Yelp Analytics Engine](https://github.com/nigel-george/yelp-analytics-engine)
*A multi-tier Medallion architecture data pipeline processing massive public datasets.*
- **Scale & Tech:** Python | PostgreSQL | dbt Core | Pydantic V2 | Docker | **7M Records**
- **Architecture:** Built a **Bronze → Silver → Gold** pipeline running on Dockerized PostgreSQL. Implemented SHA-256 row hashing for idempotent ingestion and Pydantic V2 data contracts to quarantine malformed data records.
- **Analytics Layer:** Modeled the Gold layer using **dbt Core**, deploying conditional aggregations and monthly growth metrics via window functions. Enforced a rigid testing suite (`unique`, `not_null`, `relationships`) to ensure absolute data integrity across 7M records.

---

### 📊 Professional Highlights

- **Freelance Data & Backend Engineer:** Scaled concurrent Python pipelines handling **250K+ records** with an ingestion throughput of **8K–15K records/min**, keeping data completeness above 97%. Tuned query and indexing strategies to drop key endpoint latencies by up to 76%.
- **Senior Backend Developer & Team Lead (Om Informatics):** Led 3 full-lifecycle data product releases, managing a team of 3 developers. Rewrote legacy reporting schemas and stored procedures, cutting query execution times by **40%**.

---

### 🎓 Education & Background

- **Ontario College Graduate Certificate in AI & Data Science** | Loyalist College, Toronto (2022 - 2023)
  - *Capstone:* Computer Vision real-time tracking pipeline using YOLOv7, PyTorch, and TensorFlow.
- **Master of Science in Computer Science** | SIES College, Mumbai University (Graduated with Distinction, CGPA 8.1/10)

---

### 🤝 Connect With Me

- 💼 **LinkedIn:** [linkedin.com/in/ngspace](https://linkedin.com/in/ngspace)
- 📧 **Email:** [nigelgeorgework@gmail.com](mailto:nigelgeorgework@gmail.com)
- 📂 **More Projects:** Check out my complete [GitHub Repositories](https://github.com/nigel-george?tab=repositories) page.
