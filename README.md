# Juan José Martínez

Backend & Data Engineer based in Medellín, Colombia — focused on scalable data
processing, automation, and business-critical software systems.

Currently building backend/data systems at **Innovación Analítica**
(Azure Databricks, Python/PySpark, large-scale invoice validation). Before
that: RPA/full-stack at TDP Solutions, full-stack at PITRANSFORM LLC.

**[Portfolio](https://jmartinezgr.com)** · **[LinkedIn](https://www.linkedin.com/in/juan-jose-martinez)** · **[Email](mailto:josemargri3@gmail.com)**

---

### Featured project — [AuditLake](https://github.com/jmartinezgr/retail-audit-platform)

A layered (bronze / silver / gold) data audit engine for retail invoicing,
built lakehouse-style — no Spark. Ingests multi-item invoices, runs them
through a medallion pipeline, and produces an explainable audit trail: which
rule ran, against what, and why it passed or failed.

The domain (a fictional retail chain) is invented so it can live in a public
repo, but the pipeline shape and rule engine are modeled on real high-volume
transactional-data auditing work.

`Python` · `FastAPI` · `Polars` · `Delta Lake` · `DuckDB` · `PostgreSQL` · `React` · `TypeScript`
— 18 rules (built-in + user-defined), 97 tests over the pure domain layer.

**[Live demo ↗](https://auditlake.jmartinezgr.com)** (free-tier backend, first
request can take ~30s to wake up)

---

### Stack

| | |
|---|---|
| **Backend** | Python, FastAPI, Django REST, Node.js, NestJS, SQL |
| **Data** | PySpark, Databricks, Delta Lake, Polars, Pandas, Parquet |
| **Cloud / Infra** | Azure, Docker, Kubernetes, Redis, CI/CD |
| **Automation / Frontend** | Selenium, SAP UI5, RPA, React, TypeScript |

---

Less magic. More systems.
