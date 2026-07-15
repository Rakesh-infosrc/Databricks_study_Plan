# Databricks Team Study Plan — Upskilling

**Owner:** Rakesh Reddy
**Duration:** 6 Weeks · 3 Days/Week (2 Theory + 1 Hands-On)
**Aligned to:** Data Engineering  Playbook (Medallion architecture, naming conventions, Git/PR standards)
**Platform:** Databricks Free Edition (serverless-only — no custom clusters/GPUs)



## Repo Structure
```
databricks-coe-study-plan/
├── README.md
├── week-01-lakehouse-delta/
│   ├── notes/
│   ├── hands-on/
│   └── interview-review.md
├── week-02-unity-catalog/
├── week-03-spark-core/
├── week-04-spark-performance/
├── week-05-enterprise-de/
├── week-06-production-accelerator/
└── resources/
```

## Schedule

| Week | Theme | Day 1 (Theory) | Day 2 (Theory) | Day 3 (Hands-On) |
|---|---|---|---|---|
| 1 | Lakehouse & Delta Lake | Mon Jul 20 — Lakehouse fundamentals, workspace, compute types | Wed Jul 22 — Delta Lake architecture, ACID, schema evolution, time travel | Fri Jul 24 — Delta tables, OPTIMIZE/Z-ORDER, mock interview |
| 2 | Unity Catalog & Workflows | Mon Jul 27 — Unity Catalog, external locations, RLS/masking | Wed Jul 29 — Workflows, jobs, scheduling, notifications | Fri Jul 31 — Configure UC objects, RLS, multi-task job, review |
| 3 | Spark Core | Mon Aug 3 — Spark architecture, DataFrames vs RDD | Wed Aug 5 — Transformations/actions, DAG, Catalyst/Tungsten | Fri Aug 7 — DAG inspection, query plans, whiteboard walkthrough |
| 4 | Spark Performance | Mon Aug 10 — AQE, partitioning, shuffle | Wed Aug 12 — Broadcast join, caching, file formats | Fri Aug 14 — AQE on skewed data, join/caching benchmarks, tuning interview |
| 5 | Enterprise Data Engineering | Mon Aug 17 — ETL/ELT, Medallion, CDC, SCD | Wed Aug 19 — Error handling, monitoring, cost optimization | Fri Aug 21 — Bronze→Silver→Gold pipeline, SCD Type 2, logging, review |
| 6 | Production & Accelerator | Mon Aug 24 — Git/Repos, CI/CD, unit testing, code standards | Wed Aug 26 — Reusable framework patterns, accelerator planning | Fri Aug 28 — Build accelerator, CI/CD + unit tests, final presentation |

> Free Edition notes: External Locations & Storage Credentials, Cluster Policies/Autoscaling, and Photon are **concept-only** (serverless-only environment). Jobs are capped at 5 concurrent tasks.



## Weekly Rhythm
1. Theory Day 1 & 2 — individual study, notes committed by EOD
2. Hands-On Day 3 — pair/group lab, notebook + PR
3. Weekly mock interview/review — logged in `interview-review.md`, gaps flagged for revisit

