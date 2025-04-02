# Data Warehouse & Analytics Project
Welcome to my Data Warehouse and Analytics Project repository! 🎉  
This is a passion project showcasing a full-fledged data warehousing and analytics solution—from crafting a robust data warehouse to delivering meaningful, actionable insights. Built as a portfolio piece, it reflects real-world data engineering and analytics practices I’ve honed over time.

## 🏗️ Data Architecture
This project is built on the **Medallion Architecture**, with three distinct layers:  
- **Bronze Layer**: Raw, unfiltered data straight from the source—ingested from CSV files into a SQL Server database.  
- **Silver Layer**: Where the magic of cleansing, standardizing, and normalizing happens to prep the data for analysis.  
- **Gold Layer**: Polished, business-ready data shaped into a star schema, perfect for reporting and analytics.

## 📖 What’s This Project About?
Here’s the rundown:  
- **Data Architecture**: A modern data warehouse designed with the Medallion Architecture (Bronze, Silver, Gold).  
- **ETL Pipelines**: Extracting data from source systems, transforming it, and loading it into the warehouse.  
- **Data Modeling**: Crafting fact and dimension tables optimized for fast, analytical queries.  
- **Analytics & Reporting**: Building SQL-driven reports and dashboards that turn data into decisions.  

This repo is a goldmine for anyone—professionals or students—looking to flex their skills in:  
- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Design  
- Data Modeling  
- Data Analytics  

## 🛠️ Tools & Resources (All Free!)  
- **Datasets**: CSV files provided for the project (ERP and CRM data).  
- **SQL Server Express**: A lightweight database server to host your work.  
- **SQL Server Management Studio (SSMS)**: A handy GUI for managing your database.  
- **Git Repository**: Set up a GitHub account to track and collaborate on your code.  
- **Draw.io**: Sketch out architectures, models, and flows (files included!).  
- **Notion**: Grab the project template and detailed steps from my Notion pages:  
  - [Project Template](https://notion.so)  
  - [Project Phases & Tasks](https://notion.so)  

## 🚀 Project Requirements
### Building the Data Warehouse (Data Engineering)  
**Goal**: Create a modern data warehouse using SQL Server to unify sales data for reporting and decision-making.  
**Details**:  
- **Data Sources**: Import data from ERP and CRM systems (provided as CSVs).  
- **Data Quality**: Clean up inconsistencies and errors before analysis.  
- **Integration**: Merge both sources into a single, query-friendly data model.  
- **Scope**: Focus on the latest dataset—no historical data tracking needed.  
- **Documentation**: Clear, concise data model docs for business and analytics teams.  

### BI: Analytics & Reporting (Data Analysis)  
**Goal**: Use SQL to uncover insights into:  
- Customer Behavior  
- Product Performance  
- Sales Trends  
These metrics empower stakeholders to make smart, strategic moves.  

Check out `docs/requirements.md` for the full scoop!

## 📂 Repository Structure
data-warehouse-project/
│
├── datasets/                   # Raw ERP and CRM data (CSVs)
│
├── docs/                       # Documentation and diagrams
│   ├── etl.drawio             # ETL techniques and methods
│   ├── data_architecture.drawio # Project architecture diagram
│   ├── data_catalog.md        # Dataset fields and metadata
│   ├── data_flow.drawio       # Data flow diagram
│   ├── data_models.drawio     # Star schema models
│   ├── naming-conventions.md  # Naming rules for consistency
│
├── scripts/                    # SQL scripts for the pipeline
│   ├── bronze/                # Raw data extraction and loading
│   ├── silver/                # Data cleaning and transformation
│   ├── gold/                  # Analytical model creation
│
├── tests/                      # Scripts for testing and quality checks
│
├── README.md                   # You’re reading it!
├── LICENSE                     # MIT License details
├── .gitignore                  # Git ignore rules
└── requirements.txt            # Project dependencies



## 🌟 About Me
Hey, I’m Ehab Elnadi—a data analyst who’s all about turning raw data into stories that matter. I live for the thrill of building pipelines, designing models, and uncovering insights.  

Let’s connect! Find me on:  
- [LinkedIn](https://linkedin.com/in/ehab-elnadi)  
- [Twitter/X](https://twitter.com/ehab_elnadi)  
- [Email](mailto:ehab.elnadi@example.com)  
