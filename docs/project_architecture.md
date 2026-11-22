Project Architecture

1. Introduction

The Nigeria Macroeconomic Indicators Data Pipeline is designed to collect, store, process and validate economic data about Nigeria using publicly available information from the World Bank.

2. Data Source

The primary data source is the World Bank Open Data API.

The project will collect selected economic indicators, including:

- GDP growth
- Inflation rate
- Total population

3. Pipeline Architecture

The pipeline will follow these stages:

Stage 1: Data Extraction

Python will connect to the World Bank API and retrieve the selected Nigerian economic indicators.

Stage 2: Raw Data Storage

The original data will be saved in its raw format to preserve the source information.

Stage 3: Data Transformation

Python and SQL will be used to clean, organise and transform the collected data.

Stage 4: Data Validation

Data quality checks will identify missing values, duplicate records and inconsistencies.

Stage 5: Processed Data Storage

The cleaned and validated data will be stored in a structured format for analysis and reporting.

4. Technology Stack

- Python – Data extraction and processing.
- SQL – Data transformation and querying.
- DuckDB – Local analytical database.
- GitHub – Version control and documentation.

5. Expected Output

The final output will be a structured dataset containing selected Nigerian macroeconomic indicators, suitable for further analysis and visualisation.

6. Implementation Status

This document describes the planned architecture. The pipeline components will be implemented and tested progressively.
