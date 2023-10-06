Udacity final Azure Data Engineering Project

# Project Introduction
The City of New York would like to develop a Data Analytics platform on Azure Synapse Analytics to accomplish two primary objectives:

Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees.
You have been hired as a Data Engineer to create high-quality data pipelines that are dynamic, can be automated, and monitored for efficient operation. The project team also includes the city’s quality assurance experts who will test the pipelines to find any errors and improve overall data quality.

The source data resides in Azure Data Lake and needs to be processed in a NYC data warehouse in Azure Synapse Analytics. The source datasets consist of CSV files with Employee master data and monthly payroll data entered by various City agencies.

## Tools Used
Azure data factory (ADF)- data flows and pipelines
Azure Synapse - created data warehouse

## Set up
Needed to create Azure gen 2 storage account to store the original csv data files
Created an intermediate Azure SQL DB
Created a Synapse Datawarehouse
Created 6 dataflows to move data around and do some transformations
Created 3 Pipelines to move the data from csv to Synapse

## Data Modeling for Analytics
The end result of this project is to provide payroll analytics information for NYC payroll data.

To get there, a star schema was created. Below is the data model used for analytics

![data model](https://github.com/chrisselig/de_udacity_nycdata_project/blob/main/01_images_for_readme/data_model.png)

# Dashboard
Below is the dashboard created from the data model

![dashboard](https://github.com/chrisselig/de_udacity_nycdata_project/blob/main/dashboard.png)
