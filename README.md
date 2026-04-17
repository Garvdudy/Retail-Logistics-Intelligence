# Retail Logistics Intelligence

This project is a complete end-to-end data analytics system designed to simulate how a retail and logistics business operates.

The focus is not just on building dashboards, but on creating a full workflow - starting from raw data, cleaning it, structuring it into a relational database, performing deep analysis, and generating meaningful business insights.

---

## Project Objective

The goal of this project is to:

- Build a structured and scalable data system
- Perform advanced SQL-based analysis
- Understand real business scenarios (sales, logistics, returns, fraud)
- Create data-driven insights using BI tools

This project reflects how real data analysts work in industry environments.

---

## Data Architecture

The dataset is designed as a relational system with multiple connected tables:

- suppliers  
- categories
- products  
- orders  
- shipments 
- customers  
- order_items  

Key characteristics:

- ~300K+ transactional records  
- Multi-country setup (Canada + USA)  
- 18 months of data  
- Realistic business patterns (returns, fraud flags, bulk orders, stock gaps)

---

## Tech Stack

### Data Processing & Cleaning
- **Excel** → initial cleaning and validation  
- **Python (Pandas, NumPy)** → transformation, automation, deeper analysis  

### Database & SQL
- **PostgreSQL** → relational database design, schema creation, and advanced SQL querying  

### Scalable Data (Learning Layer)
- **Databricks** → basic data processing using PySpark and SQL to understand scalable workflows  

### Visualization
- **Power BI / Tableau** → dashboards, KPIs, and business insights  

### Project Management
- **GitHub** → version control and structured development  
- **Jira** → task tracking and workflow management  
- **Notion** → documentation and planning  

---

## Workflow

### 1. Data Cleaning
- Clean raw data using Excel
- Deleted unwanted columns and add where needed using logics
- Handle inconsistencies, formatting issues, and missing values  

### 2. Database Design (PostgreSQL)
- Create normalized tables  
- Define primary and foreign keys  
- Import cleaned data into PostgreSQL  

### 3. SQL Analysis
- Perform complex joins across multiple tables  
- Analyze customer behavior and sales trends  
- Identify supply-demand gaps  
- Detect returns and fraud patterns
- Created Views and Procedure
- Perform CTEs and Trigger Queries

### 4. Python Analysis
- Perform deeper analysis and tried automation where needed 
- Generate additional insights and custom visualizations  

### 5. Databricks (Exploration)
- Run basic transformations using PySpark  
- Understand scalable data workflows  
- Explored in terms of work-flow & other means
- Perform simple aggregations on large-style datasets  

### 6. Visualization
- Build interactive dashboards in Power BI / Tableau  
- Track KPIs like revenue, orders, returns, and customer segments  
- Present insights in a business-focused way  

---

## Business Problems Covered

This project is designed to solve real-world problems such as:

- High demand but low stock products  
- Customer retention vs one-time buyers  
- Regional sales performance differences  
- Return patterns by city and product  
- Fraud detection using abnormal behavior  
- Revenue contribution by category & Suppliers

---

## About Project 

- starts from raw, imperfect data  
- builds a full data pipeline  
- includes supply chain and logistics  
- focuses on real business decision-making  

---

## Final Goal

- Data cleaning and transformation  
- Analyzing Data using PostgreSQL and MySQL   
- Business Insights and recommendations
- End-to-end analytics workflow  

---
