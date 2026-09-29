<div align="center">

# Felipe Pinete
### Data Engineer & Analytics Specialist
**Modern Data Pipelines • In-Process Lakehouses • Kimball Dimensional Modeling • Power BI & SQL Tuning**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/felipe-pinete-302303177)
[![Email](https://img.shields.io/badge/Email-Felipe__pinete%40outlook.com-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:Felipe_pinete@outlook.com)
[![Location](https://img.shields.io/badge/Location-Brazil-1B1F23?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

### About Me

Engineer focused on **Data Platforms**, **Business Intelligence (BI)**, **ELT/ETL Pipelines**, and **High-Performance Analytical Systems**.

My core engineering focus centers on bridging raw transactional data into actionable executive intelligence:
- Building **in-process columnar Lakehouses** (`DuckDB`, `Polars`, `Apache Parquet`) with Medallion architecture (Bronze ➔ Silver ➔ Gold).
- Designing **enterprise dimensional models** (Ralph Kimball Star Schema, Fact & Dimension tables, Slowly Changing Dimensions).
- Structuring **executive BI dashboards** and automated KPI computation (`Power BI`, `DAX`, operational metrics like CSAT, NPS, and MTTR).
- Advanced relational query tuning and indexing in **Microsoft SQL Server** (T-SQL, Window Functions, Covering Indexes, Execution Plan diagnostics).
- Grounded with strong software engineering principles in `Python` and `C#` / `.NET 9` Clean Architecture.

---

### Tech Stack & Core Competencies

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Data Engineering & Lakehouses</h4>
      <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB" />
      <img src="https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white" alt="Polars" />
      <img src="https://img.shields.io/badge/Apache%20Parquet-5B6998?style=flat-square&logo=apache&logoColor=white" alt="Parquet" />
      <img src="https://img.shields.io/badge/Python%203-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <br /><br />
      <ul>
        <li>In-process Medallion lakehouse stages (Bronze / Silver / Gold).</li>
        <li>Automated ELT/ETL pipelines with quarantine data quality gates.</li>
        <li>High-throughput batch ingestion and SIMD vectorization.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>Business Intelligence & Analytics</h4>
      <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI" />
      <img src="https://img.shields.io/badge/DAX-EAA023?style=flat-square&logo=dax&logoColor=white" alt="DAX" />
      <img src="https://img.shields.io/badge/Ralph%20Kimball-Star%20Schema-0284C7?style=flat-square" alt="Kimball" />
      <img src="https://img.shields.io/badge/Executive%20BI-DataMarts-10B981?style=flat-square" alt="BI" />
      <br /><br />
      <ul>
        <li>Dimensional data modeling (Star Schema, Fact/Dim tables, SCD Type 2).</li>
        <li>Executive KPI engines (CSAT, Net Promoter Score, SLA, MTTR).</li>
        <li>Dynamic temporal slicing, cohort analysis, and customer RFM segmentation.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>Databases & SQL Performance Tuning</h4>
      <img src="https://img.shields.io/badge/SQL%20Server-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
      <img src="https://img.shields.io/badge/T--SQL-4169E1?style=flat-square&logo=sqlite&logoColor=white" alt="T-SQL" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/Query%20Optimization-Execution%20Plans-EA580C?style=flat-square" alt="Tuning" />
      <br /><br />
      <ul>
        <li>Execution plan analysis, index architecture (Seek vs Scan, Covering Indexes).</li>
        <li>Analytical T-SQL: Window Functions (`ROW_NUMBER`, `NTILE`, `DENSE_RANK`), CTEs.</li>
        <li>DataMart staging architecture, concurrency, and lock remediation.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>Systems Engineering & Automation</h4>
      <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white" alt="C#" />
      <img src="https://img.shields.io/badge/.NET%208%20%2F%209-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <br /><br />
      <ul>
        <li>Clean Architecture & Domain-Driven Design (DDD) backend APIs.</li>
        <li>Automated background daemons, IPC bridges, and ERP integrations.</li>
        <li>CI/CD pipelines with GitHub Actions and deterministic quality gates.</li>
      </ul>
    </td>
  </tr>
</table>

---

### Featured Data Platforms & Architectures

| System | Focus Area | Core Technologies | Architectural Highlights |
| :--- | :--- | :--- | :--- |
| **[NexStream](https://github.com/FelipeLipeee/nexstream)** | Real-Time CDC & Outbox Engine | Python 3.12, SQL Server CDC, n8n, Parquet | **7,200+ events/sec** streaming, zero table locks on OLTP, atomic Transactional Outbox, LRU idempotency guard. |
| **[NexLake](https://github.com/FelipeLipeee/nexlake)** | In-Process Medallion Lakehouse | DuckDB, Polars, Snappy Parquet, Kimball | **47.5x faster** than Pandas on 1M rows, zero-copy OLAP views, SCD Type 2 history, RFM customer segmentation mart. |
| **[TecDesk Dashboard](https://github.com/FelipeLipeee/tecdesk-dashboard)** | Operational BI & Helpdesk DataMart | SQL Server, Python ETL, React 19, Recharts | Executive KPI engine (CSAT, MTTR, SLA), live audit conversation trail, automated background ETL synchronization. |

---

### Engineering & Data Principles

- **Data Truth in Modeling:** Rigorous dimensional modeling (Kimball) over ad-hoc flat tables to ensure reporting consistency and single source of truth.
- **KISS & YAGNI:** Relentless rejection of premature abstractions, unused libraries, and unneeded infrastructure layers.
- **Deterministic Validation:** Systems correctness is anchored on deterministic compiler checks, linters, and regression suites—not probabilistic assumptions.
- **Zero Secrets in Source:** Absolute credential isolation via runtime environment vaults; zero plain-text secrets in version control.

---

### Activity & GitHub Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=FelipeLipeee&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="Felipe's GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FelipeLipeee&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" height="165" />
</div>

<br />

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=FelipeLipeee&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

<div align="center">
  <sub>Engineered with precision. All rights reserved.</sub>
</div>
