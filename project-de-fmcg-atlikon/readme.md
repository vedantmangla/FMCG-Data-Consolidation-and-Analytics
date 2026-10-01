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

## 📁 Project Structure
FMCG-Data-Consolidation-and-Analytics/
│
├── 0_data/
│   └── Raw and processed datasets
│
├── 1_codes/
│   └── Data processing and transformation code
│
├── 2_dashboarding/
│   └── Dashboard and analytical outputs
│
├── resources/
│   └── Supporting project resources
│
└── README.md

## 🔄 Data Engineering Workflow
1. Data Ingestion

Raw FMCG datasets are organized under the 0_data directory.

The data contains operational information related to products, outlets, sales, and other business attributes.

2. Data Cleaning

The raw datasets are cleaned and validated before downstream analysis.

Key operations include:

Handling missing values
Removing duplicate records
Standardizing categorical values
Identifying invalid records
Validating numerical fields
Checking data consistency
3. Data Transformation

The cleaned datasets are transformed into structured analytical datasets.

Transformations include:

Joining related datasets
Creating derived fields
Standardizing business dimensions
Aggregating transactional data
Preparing data for analytical queries

## 🧱 Data Modelling
The project uses dimensional modelling concepts to organize data for analytical workloads.

Fact Data

Contains measurable business metrics such as:

Sales
Quantity
Revenue
Product performance
Outlet performance
Dimension Data

Provides descriptive context around the business metrics, including:

Products
Outlets
Categories
Locations
Time

This structure enables analysis of product and outlet performance across different business dimensions.
