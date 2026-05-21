# AnalyticsHub

A collection of data analytics, reporting, and data migration projects demonstrating experience in:

- Data Analysis
- Business Intelligence
- Dashboard Development
- SQL & Python Data Processing
- Data Migration & Validation
- ETL Concepts
- Reporting Automation

> Note: All dashboards and datasets used in this repository are sample or recreated datasets for demonstration purposes only. No confidential or client-specific data is included.

---

## Projects Included

### 1. Business Analytics & Reporting
Focused on data analysis, KPI tracking, dashboard automation, and business insights generation using SQL, Python, Power BI, and Tableau.

### 2. Data Migration & Data Validation
Focused on data mapping, cleansing, migration validation, integrity checks, and cross-system consistency during enterprise system transitions.

---
## Data Flow
```
SQL Database
      ↓
SQL Query
      ↓
pd.read_sql()
      ↓
Python DataFrame
      ↓
Pandas Transformation
      ↓
Power BI / Tableau Dashboard
```

## Tools & Technologies

- SQL
- Python (Pandas, NumPy)
- Power BI
- Tableau
- Snowflake
- Excel
- Apache Spark

---

## Key Areas Demonstrated

- Data Cleaning & Transformation
- Dashboard Development
- Reporting Automation
- ETL & Data Validation
- KPI Analysis
- Data Quality Checks
- Metadata Standardization
- Business Insights Generation

---

## Key Skills Demonstrated

- Data Analysis
- KPI Reporting
- Dashboard Automation
- Data Transformation
- Business Intelligence
- SQL Querying
- Python Data Processing

## Tools & Technologies

- Power BI
- Tableau
- SQL
- Python (Pandas, NumPy)
- Snowflake
- Excel
- Apache Spark

## Sample Analytics
* Extracted SQL data
* Removed duplicates
* Handled missing values
* Aggregated sales by region
```python

df = pd.read_sql(query, connection)

df = df.drop_duplicates()

df["Sales"] = df["Sales"].fillna(0)

region_sales = df.groupby("Region")["Sales"].sum()
```
## Sample Deliverables

- Interactive KPI dashboards
- Automated reporting workflows
- Business performance analysis
- Trend and usage analysis

## Migration Workflow

The project followed a structured ETL-based data migration workflow to move data from a legacy PHP/MySQL application into a modern CMS platform integrated with ASP.NET/.NET technologies.

### Workflow Steps

1. Data Extraction
   - Extracted structured data from legacy MySQL databases
   - Used SQL queries and PL/SQL views for data retrieval

2. Data Mapping
   - Mapped source database fields to target CMS schema
   - Defined transformation and compatibility rules

3. Data Cleansing
   - Removed duplicate and inconsistent records
   - Standardized metadata and formatting
   - Validated mandatory fields and null values

4. Data Transformation
   - Converted data into target CMS-compatible formats
   - Applied business rules and formatting logic

5. Data Loading
   - Loaded transformed datasets into the new CMS environment
   - Executed migration scripts and batch inserts

6. Validation & Integrity Checks
   - Compared source vs target record counts
   - Verified data completeness and accuracy
   - Checked for duplicates, missing values, and schema consistency

7. Post-Migration Verification
   - Collaborated with technical teams for testing and verification
   - Ensured successful migration and consistent system behavior

### Migration Flow
```
Legacy PHP/MySQL System
        ↓
Data Extraction
        ↓
Data Mapping
        ↓
Data Cleansing
        ↓
Data Transformation
        ↓
Load into New CMS
        ↓
Validation & Integrity Checks
        ↓
Post-Migration Verification
Load into New CMS
      ↓
Validation & Integrity Checks
```
