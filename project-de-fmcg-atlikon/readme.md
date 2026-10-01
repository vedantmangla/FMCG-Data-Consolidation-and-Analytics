# FMCG Data Consolidation & Analytics

An end-to-end Data Engineering and Analytics project focused on consolidating FMCG sales and operational data into structured, analytics-ready datasets.

## 🚀 Project Overview

FMCG businesses generate data from multiple operational sources such as products, outlets, sales transactions, and inventory. This project focuses on transforming raw source data into clean, structured datasets that can be used for analytics and business decision-making.

The project covers:

- Data ingestion and consolidation
- Data cleaning and validation
- Data transformation
- Data quality checks
- Data modelling
- Business KPI generation
- Dashboarding and analytics

---

## 🏗️ Project Architecture

```text
                    SOURCE DATA
                        │
                        ▼
              ┌───────────────────┐
              │     0_data/       │
              │ Raw Source Files  │
              └─────────┬─────────┘
                        │
                        ▼
              ┌───────────────────┐
              │    1_codes/       │
              │ Data Processing   │
              │ & Transformations │
              └─────────┬─────────┘
                        │
                        ▼
              ┌───────────────────┐
              │ Cleaned / Curated │
              │ Analytical Data   │
              └─────────┬─────────┘
                        │
                        ▼
              ┌───────────────────┐
              │ 2_dashboarding/   │
              │ KPI & Analytics   │
              └───────────────────┘
                        │
                        ▼
                 Business Insights
