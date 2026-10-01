# FMCG Data Consolidation & Analytics

An end-to-end **Data Engineering and Analytics project** focused on consolidating, cleaning, transforming, modelling, and analyzing FMCG data to create reliable and analytics-ready datasets for business decision-making.

---

## 📌 Project Overview

FMCG businesses generate data across products, outlets, sales, categories, locations, and other operational dimensions. When these datasets come from different sources, inconsistencies, missing values, duplicate records, and incompatible formats can make downstream analysis unreliable.

This project builds an end-to-end workflow to transform raw FMCG data into structured datasets that can be used for analytics and business decision-making.

The project covers:

- Data ingestion and consolidation
- Data exploration and profiling
- Data cleaning and preprocessing
- Data quality validation
- Data transformation
- Analytical data modelling
- SQL-based analysis
- Predictive analysis
- KPI generation
- Dashboarding and business insights

---

## 🏗️ Project Architecture

~~~text
                         SOURCE DATA
                              │
                              ▼
                    ┌───────────────────┐
                    │      0_data/      │
                    │                   │
                    │ Raw FMCG Data     │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │     1_codes/      │
                    │                   │
                    │ Cleaning          │
                    │ Transformation    │
                    │ Validation        │
                    │ Analysis          │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │  Curated Dataset  │
                    │                   │
                    │ Cleaned &         │
                    │ Analytics-Ready   │
                    │ Data              │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │ 2_dashboarding/   │
                    │                   │
                    │ KPIs & Dashboards │
                    │ Business Analysis │
                    └─────────┬─────────┘
                              │
                              ▼
                     BUSINESS INSIGHTS
~~~

---

## 📂 Project Structure

~~~text
FMCG-Data-Consolidation-and-Analytics/
│
├── 0_data/
│   └── Raw and processed FMCG datasets
│
├── 1_codes/
│   └── Data cleaning, transformation and analysis code
│
├── 2_dashboarding/
│   └── Dashboards and analytical outputs
│
├── resources/
│   └── Supporting project resources
│
└── README.md
~~~

### `0_data/`

Contains the raw and processed datasets used throughout the project.

### `1_codes/`

Contains the scripts and notebooks used for data cleaning, transformation, analysis, and processing.

### `2_dashboarding/`

Contains dashboards and analytical outputs generated from the processed datasets.

### `resources/`

Contains supporting project resources and reference materials.

---

## 🔄 Data Engineering Workflow

### 1. Data Ingestion

The project starts with raw FMCG datasets containing operational information related to products, outlets, sales, and other business attributes.

The source files are organized under the `0_data` directory before being processed.

### 2. Data Exploration

The datasets are explored to understand their structure and identify potential issues before transformation.

The exploration includes:

- Dataset dimensions
- Column types
- Missing values
- Duplicate records
- Unique values
- Categorical distributions
- Numerical ranges
- Relationships between datasets
- Potential data-quality issues

### 3. Data Cleaning

The raw datasets are cleaned and standardized before being used for downstream analytics.

Key operations include:

- Handling missing values
- Removing duplicate records
- Standardizing categorical values
- Identifying invalid records
- Correcting inconsistent formats
- Validating numerical fields
- Checking data consistency

### 4. Data Transformation

The cleaned datasets are transformed into structured analytical datasets.

Transformations include:

- Joining related datasets
- Creating derived fields
- Standardizing business attributes
- Aggregating transactional data
- Creating analytical metrics
- Preparing datasets for analytical queries

---

## 🛡️ Data Quality

Data quality is treated as an important part of the overall pipeline.

The project considers checks for:

- Missing values
- Duplicate records
- Invalid values
- Data-type consistency
- Referential consistency
- Valid business ranges
- Consistent categorical values

These checks help ensure that unreliable source data does not propagate into downstream analytics.

---

## 🧱 Data Modelling

The project applies dimensional modelling concepts to organize cleaned data for analytical workloads.

### Fact Data

Fact data contains measurable business metrics such as:

- Sales
- Revenue
- Quantity
- Product performance
- Outlet performance

### Dimension Data

Dimension data provides descriptive context around business metrics, including:

- Products
- Outlets
- Categories
- Locations
- Time

This structure allows business metrics to be analyzed across multiple dimensions.

---

## 🔗 Data Transformation

After cleaning and validation, the datasets are transformed into analytical structures.

The transformation process includes:

- Joining related datasets
- Creating derived columns
- Standardizing business dimensions
- Aggregating transactional data
- Creating business metrics
- Preparing data for downstream reporting

SQL and Python are used to perform the required transformations and analysis.

---

## 🧮 SQL Analysis

SQL is used for analytical querying and business logic.

The project applies concepts such as:

- Joins
- Aggregations
- `GROUP BY`
- `HAVING`
- `CASE`
- Common Table Expressions (CTEs)
- Window functions
- Subqueries
- Ranking
- Analytical calculations

These techniques are used to generate business metrics and answer analytical questions.

---

## 🐍 Python Data Processing

Python is used for data processing, exploration, transformation, and analysis.

Key libraries include:

- **Pandas** — Data manipulation and transformation
- **NumPy** — Numerical processing
- **Scikit-learn** — Predictive modelling
- **Matplotlib / Seaborn** — Data visualization where applicable

---

## 🤖 Predictive Analysis

The project also incorporates predictive analysis to complement descriptive analytics.

The modelling workflow follows:

~~~text
Clean Dataset
      ↓
Feature Preparation
      ↓
Train / Test Split
      ↓
Model Training
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Business Interpretation
~~~

Predictive outputs can be compared with actual performance to identify potential business opportunities and underperforming product-outlet combinations.

---

## 📊 Analytics & Dashboarding

The processed datasets are used to generate business KPIs and analytical insights.

Key analysis areas include:

- Outlet performance
- Product performance
- Category-level sales
- Revenue contribution
- Outlet-level comparisons
- Product-outlet performance
- Business opportunities
- Underperformance analysis

The dashboarding and analytical outputs are available in the `2_dashboarding` directory.

---

## 📈 Business Use Cases

The project can help answer questions such as:

- Which outlets are performing best?
- Which outlets are underperforming?
- Which products generate the most revenue?
- Which categories contribute most to sales?
- Which product-outlet combinations have performance gaps?
- Where are potential revenue opportunities?
- Which areas require further investigation?
- How can analytical insights support business decisions?

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **Python** | Data processing and analysis |
| **Pandas** | Data cleaning and transformation |
| **NumPy** | Numerical processing |
| **Scikit-learn** | Predictive modelling |
| **SQL** | Data querying and analytical transformations |
| **Excel** | Business analysis and scenario modelling |
| **Git** | Version control |
| **GitHub** | Project versioning and collaboration |

---

## 🔑 Data Engineering Concepts

This project demonstrates practical understanding of:

- ETL workflows
- Data ingestion
- Data exploration
- Data cleaning
- Data validation
- Data transformation
- Data quality
- Analytical SQL
- Data modelling
- Fact and dimension concepts
- KPI generation
- Predictive analytics
- Dashboarding
- Business intelligence

---

## 🔄 End-to-End Pipeline

~~~text
                   RAW FMCG DATA
                         │
                         ▼
                  DATA INGESTION
                         │
                         ▼
                  DATA EXPLORATION
                         │
                         ▼
                  DATA CLEANING
                         │
                         ▼
                DATA QUALITY CHECKS
                         │
                         ▼
                 TRANSFORMATION
                         │
                         ▼
                  DATA MODELLING
                         │
                         ▼
              ┌──────────┴──────────┐
              │                     │
              ▼                     ▼
        SQL ANALYSIS        PREDICTIVE MODEL
              │                     │
              └──────────┬──────────┘
                         ▼
                    BUSINESS KPIs
                         │
                         ▼
                     DASHBOARD
                         │
                         ▼
                  BUSINESS INSIGHTS
~~~

---

## 📌 Key Learning Outcomes

Through this project, the following concepts are demonstrated:

1. Transforming raw business data into structured analytical datasets.
2. Identifying and handling data-quality issues.
3. Using SQL for analytical business logic.
4. Using Python and Pandas for data processing.
5. Applying dimensional modelling concepts.
6. Using predictive modelling to complement descriptive analytics.
7. Translating technical data outputs into business KPIs.
8. Communicating insights through dashboards.

---

## 🚀 Future Improvements

Potential extensions include:

- Automating data ingestion
- Implementing incremental data loading
- Adding workflow orchestration using Airflow
- Migrating processing to a cloud data platform
- Implementing Delta Lake for reliable storage
- Adding automated data-quality tests
- Implementing pipeline monitoring and alerting
- Adding real-time streaming using Kafka
- Implementing CI/CD for data pipelines

---

## 👨‍💻 Author

**Vedant Mangla**

B.Tech — Mathematics & Computing  
Delhi Technological University

---

## ⭐ Project Focus

**Raw Data → Cleaning → Validation → Transformation → Modelling → Analytics → Business Insights**
