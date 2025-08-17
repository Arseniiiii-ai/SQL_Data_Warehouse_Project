# Data Warehouse and Analytics Project 

Hello there !
Welcome to the **Data Warehouse and Analytics Project** repository!
This project showcases a complete analytics and data warehousing solution, covering everything from constructing the warehouse to generating actionable insights, and is designed as a portfolio piece that demonstrates industry best practices in data engineering and analytics.

---

## 🛠️ Project Requirements 

### Building the Data Warehouse (Data Engineering)

#### Objective 
Build a modern SQL Server–based data warehouse to integrate sales data, supporting analytical reporting and data-driven decision-making.

#### Specifications
- **Data Sources**: Load data from two source systems (ERP and CRM) supplied in CSV format.
- **Data Quality**: Clean and address data quality issues before performing analysis.
- **Integration**: Merge both sources into a unified, user-friendly data model optimized for analytical queries.
- **Scope**: Work exclusively with the latest dataset; historical data storage is not required.
- **Documentation**: Deliver clear documentation of the data model to serve the needs of both business stakeholders and analytics teams.

---

<img width="1048" height="597" alt="PNG Draw io (3)" src="https://github.com/user-attachments/assets/92569bbe-4101-4197-98ee-c94b0c7367f4" />

**1. Bronze Layer:** Stores raw data as is from the source systems. Data is ingested from CSV Files into SQL Server Database.

**2. Silver Layer:** This layer includes data cleansing, strandardization, and normalization processes to prepare data for analysis.

**3. Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.


---

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Create SQL-based analytics to provide detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights provide stakeholders with vital business metrics to guide strategic decision-making.

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE), allowing you to use, modify, and distribute it with proper attribution.

## 🙋‍♂️ About Me

Hi there! I'm **Arsen Baqtygaliev Quanishuly**.I'm first degree student in Astana IT University and i love to share something helpful for people who want to develop knowledge in Data Science, Data Engineering, and Data Analytics))  

