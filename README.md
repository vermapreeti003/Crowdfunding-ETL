# Crowdfunding-ETL
# Overview
Independent Funding is a crowdfunding platform for funding independent projects or ventures. Independent Funding has been growing, so now it needs to move all their accessible data from one large Excel file onto a PostgreSQL database. Therefore, our task was to do the following:

Extracting and transforming the data from a large Excel files into CSV files.
Creating a PostgreSQL database and tables by using an ERD.
Loading the CSV files into the database.
Performing SQL queries to generate reports for stakeholders.
## Aim
The aim of this project is to help the company build a database with SQL. This way, the analytics team will be able to perform analysis and create reports for company stakeholders as well as individuals who donate to projects..
## Analysis of Data and Results
The ETL process for Independent Funding is divided into the following steps:

## Step 1: Extract the Data
Using Python and Pandas we have extracted.
To extract these CSV files 2 methods were used:

* Python dictionary method.
* Regular expression method.
## Step 2: Transform and Clean Data
Using Python, Pandas, and data cleaning strategies, we have transformed the data via formatting, splitting, converting data types, and restructuring to create DataFrames that can be loaded into a postgreSQL database as a CSV file.

When finishing this step, we have 5 CSV cleaned files saved as:

contacts.csv
category.csv
subcategory.csv
capaign.csv
backers.csv

## Step 3: Create an ERD and Table Schema, and Load Data
In order to load the cleaned datasets as CSV files into an SQL database we started by creating an Entity Relationship Diagram (ERD) using Quick DBD website (https://www.quickdatabasediagrams.com/).
## Step 4: SQL Analysis
After creating the crowdfunding database, it has become easy to to perform analysis and create reports for company stakeholders.

## Summary
As we have seen in this project, the ETL process facilitates performance and helps in performing data analysis on database in an easier and faster way using SQL queries.
