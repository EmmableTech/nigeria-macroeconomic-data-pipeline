Nigeria Macroeconomic Indicators Data Pipeline

1. Project Overview

The Nigeria Macroeconomic Indicators Data Pipeline is a data engineering project designed to collect, process, validate and organise important economic indicators about Nigeria.

The project uses publicly available data from the World Bank Open Data API to demonstrate how raw economic data can be transformed into structured datasets suitable for analysis and reporting.

2. Problem Statement

Economic indicators such as Gross Domestic Product (GDP), inflation and population are important for understanding a country's economic performance.

However, data collected from different sources or in different formats can be difficult to organise, clean and analyse.

This project aims to build a simple and reliable data pipeline that automates the collection and processing of selected Nigerian macroeconomic indicators.

3. Project Objectives

The main objectives are to:

- Collect Nigeria's macroeconomic data from the World Bank API.
- Store the original data in a structured format.
- Clean and transform raw data using Python and SQL.
- Validate the processed data for accuracy and completeness.
- Produce organised datasets ready for further analysis.

4. Data Source

Primary source: World Bank Open Data API

Website: https://data.worldbank.org/country/nigeria

API documentation: https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-about-the-indicators-api-documentation

The project will focus on selected indicators, including:

- GDP growth (annual %)
- Inflation, consumer prices (annual %)
- Population, total
- Other relevant indicators where reliable data is available.

5. Technologies

The planned technologies include:

- Python: Data extraction and processing.
- SQL: Data transformation and querying.
- DuckDB: Local analytical database.
- dbt: Data transformation and quality testing, if implemented.
- GitHub: Version control and project documentation.

6. Pipeline Architecture

The proposed workflow is:

World Bank API → Python Data Extraction → Raw Data Storage → Data Cleaning and Transformation → Data Validation → Processed Dataset.

7. Expected Deliverables

- Raw macroeconomic datasets.
- Cleaned and structured datasets.
- Python extraction and processing scripts.
- SQL transformation queries.
- Data quality checks.
- Project documentation.

8. ## Repository Structure

```text
nigeria-macroeconomic-data-pipeline/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── src/
├── sql/
├── tests/
├── docs/
├── .gitignore
└── README.md

9. Project Status

Current stage: Repository setup and project development.

The pipeline components will be implemented and tested progressively.

---

Project Category: Data Engineering
Project Owner: Blessing Emmanuel Adeola 
