# CityRetail Data Engineering Term Project

## Overview
This project simulates the work of a Data Engineer for a fictional retail chain. The goal is to design and implement an end-to-end data pipeline that transforms raw operational data into an OLAP-ready model for interactive analysis and reporting.

---

## Objectives
- **Ingest** and clean raw operational data  
- **Design** a star schema and implement it in PostgreSQL  
- **Use Python** for data ingestion and transformation  
- **Create** an OLAP model with hierarchies and calculated measures  
- **Build** interactive dashboards using Power BI  

---

## Project Parts and Tasks

### Part 1: Data Understanding and Setup
- Download the project bundle and explore the raw dataset (CSV files).  
- Identify issues such as missing data, duplicates, and inconsistent city names.  

### Part 2: Data Ingestion and Cleaning
- Use Python to ingest data from CSV files.  
- Apply transformations such as city name standardization and date parsing.  
- Output clean data ready for loading into PostgreSQL.  

### Part 3: OLAP Schema Design
- Create a star schema using the provided SQL script (`star_schema.sql`).  
- Load cleaned data into `DimProduct`, `DimStore`, `DimDate`, and `FactSales` tables.  
- Ensure referential integrity using foreign key constraints.  

### Part 4: Measures and Aggregations
- Propose and justify **business measures (KPIs)** (e.g., Revenue, Quantity Sold, Profit Margin).  
- Describe each measure and its importance for business analysis.  
- Write SQL code for calculated fields (e.g., Revenue, Profit Margin).  
- Create views or materialized views for common aggregations (e.g., Sales by Region).  
- Ensure indexes are in place for query performance.  

### Part 5: Reporting and Dashboards
- Build dashboards to visualize sales trends, store performance, and product revenue.  
- Use slicers and filters to enable drill-down by region, date, and category.  

### Part 6: Final Report and Presentation
- Submit a written report (2,500–3,000 words) describing the data pipeline, challenges, and outcomes.  
- Present the solution and dashboards in a 5-minute video screen recording (uploaded to YouTube as private with link access).  
- Include screenshots of dashboards in the report.  

---

## Deliverables (in a ZIP file: `lastname.zip`)
- Scripts (Python)  
- Cleaned datasets  
- SQL commands for data loading  
- PostgreSQL dump file (`lastname_dump.sql`)  
- Power BI dashboard file (`.pbix`)  
- Technical report (PDF or DOCX)  

---

## Grading Criteria
- **Data Cleaning & Preparation** – 25%  
- **Dimensional Modeling/Data Loading** – 10%  
- **Measures & Queries** – 15%  
- **Dashboard & Visualization** – 20%  
- **Report & Presentation** – 25%  

---

## Report Requirements
Organize the report into the following sections:  

1. **Data Understanding**  
   - Describe the project context, data sources, and initial observations about the raw data.  
   - Identify key challenges (e.g., missing data, inconsistencies, duplicates).  
   - State the expected end-result of the pipeline.  

2. **Pipeline Planning**  
   - Explain the strategy for data cleaning and transformation.  
   - Address handling of missing values, city names, dates, currencies, etc.  
   - Justify the choice of tools, technologies, and target database.  

3. **Reliability & Performance**  
   - Describe how the pipeline ensures reliability and scalability.  
   - Explain handling of reruns, incremental data loads, and failures.  
   - Discuss parallel processing, error monitoring, and bottleneck identification.  

4. **Security & Compliance**  
   - Identify sensitive data and protection methods (e.g., masking, encryption).  
   - Recommend access controls for a production environment.  

5. **Iteration & Automation**  
   - Explain the evolution from a basic approach to an improved solution.  
   - Recommend steps for automation.  

6. **Data Presentation, KPIs & Reporting**  
   - Describe the business questions the dashboards aim to answer.  
   - Highlight chosen KPIs and justify their selection.  
   - Explain dashboard structure (e.g., slicers, filters, drill-downs).  
   - Justify visualization choices (e.g., line charts for trends, bar charts for rankings).  
   - Include sample screenshots with brief descriptions.  

---

## Tips
- Use clear headings, bullet points, and diagrams/tables where helpful.  
- Demonstrate thoughtful planning and critical thinking—not just what you did, but why.  

This structured report reflects the professional mindset and best practices of a real-world data engineer. It will be evaluated alongside your code, database, and dashboards.  
