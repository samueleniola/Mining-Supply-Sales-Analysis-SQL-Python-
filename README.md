# Mining-Supply-Sales-Analysis-SQL-Python-
# ⛏️ Mining Supply Sales Analysis Project

## 📋 Project Overview

This project provides a comprehensive data analysis solution for mining supply sales data using **SQL** and **Python**. It includes data exploration, business intelligence queries, visualization dashboards, and automated reporting tools to derive actionable insights from sales transactions.

## 🎯 Project Objectives

- Analyze mining supply sales patterns and trends
- Identify top-performing products and categories
- Generate business intelligence reports automatically
- Create interactive and static visualizations
- Provide data-driven recommendations for inventory and sales strategies

## 📁 Key Insights
I analyzed 100+ transactions across 30+ mining equipment products using SQLite, DuckDB, and Pandas - all within Jupyter Notebook. I built Daily revenue dashboards with 7-day MA, ABC Pareto Analysis(80/20 rule),Price per unit tracking across 30+ products &amp; Product ranking with revenue &amp; frequency scores
## 🚀 Features

### SQL Capabilities
- **Data Loading & Schema Creation**: Import CSV data into MySQL/SQLite/DuckDB
- **Exploratory Analysis**: Data quality checks, null value detection, outlier identification
- **Business Intelligence**: Revenue analysis, product performance, time-series trends
- **Advanced Analytics**: Moving averages, Pareto analysis (80/20 rule), anomaly detection
- **Window Functions**: Ranking, cumulative sums, lead/lag analysis, percentiles

### Visualization Features
- **Static Charts**: Matplotlib/Seaborn visualizations (PNG export for reports)
- **Interactive Dashboards**: Plotly-based HTML dashboards with hover tools
- **KPI Dashboard**: Key metrics at a glance with trend indicators
- **Multiple Chart Types**: Bar, line, pie, histogram, heatmap, box plots, scatter plots

### Automation
- **Automated Email Reports**: Daily sales summaries sent to stakeholders
- **Scheduled Queries**: Recurring analysis using MySQL events
- **Data Export**: Multi-format export (CSV, Excel, JSON, HTML)

## 🛠️ Technologies Used

### Databases
| Database | Use Case | Setup Required |
|----------|----------|----------------|
| **MySQL** | Production environment | Yes (recommended) |
| **SQLite** | Local development, notebooks | No (built-in) |
| **DuckDB** | In-memory analytics, large datasets | No (pip install) |

### Python Libraries
```python
pandas==2.0.3           # Data manipulation
numpy==1.24.3           # Numerical operations
matplotlib==3.7.2       # Static visualizations
seaborn==0.12.2         # Statistical visualizations
plotly==5.15.0          # Interactive dashboards
sqlalchemy==2.0.19      # Database connections
mysql-connector-python==8.1.0  # MySQL connection
duckdb==0.9.0           # In-memory OLAP
ipython-sql==0.4.0      # SQL magic commands
pandasql==0.7.3         # SQL on DataFrames
openpyxl==3.1.2         # Excel export
