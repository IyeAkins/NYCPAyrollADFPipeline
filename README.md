# Data Integration Pipelines for NYC Payroll Data Analytics
This project focuses on building data integration pipelines for NYC payroll data analytics using Azure services. The goal is to create a robust data pipeline that extracts data from various sources, transforms it, and loads it into Azure Data Lake Gen2, Azure SQL Database, and Azure Synapse Analytics.

This project was the capstone project for the Udacity Data Engineering With Microsoft Azure Nanodegedree that I took.

## Project Overview
In this project, I

Created Linked Services: Configured connections to Azure Data Lake Gen2, Azure SQL Database, and Azure Synapse Analytics using Linked Services in Azure Data Factory.

Defined Datasets: Created datasets to provide data views of employee and payroll data in Azure Data Lake Gen2, Azure SQL Database, and Azure Synapse Analytics.

Implemented Data Flows: I used Mapping Dataflows to aggregate payroll data from Azure SQL Database and NYC Payroll history files, and moved the data to Azure Synapse Analytics.

Built Pipelines: Create pipelines containing Dataflow activities to map, transform, and load data from Azure Data Lake Gen2 to Azure SQL Database and Azure Synapse

All the JSON files for creating the pipelines are included in this repository. You can also see screenshots that were taken at each stage of the process.
