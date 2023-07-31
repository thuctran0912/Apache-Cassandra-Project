# Data Modelling with Apache Cassandra 
## Scenario
A startup called **Sparkify** wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

## Project Overview

 - I am provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.
 - I completed the pipeline by modeling the data provided on Apache Cassandra 

## Datasets

For this project, you'll be working with one dataset: `event_data`. The directory of CSV files partitioned by date. Here are examples of file paths to two files in the dataset:

> event_data/2018-11-08-events.csv 
> event_data/2018-11-09-events.csv

## Project template

I am using the project template, a Jupyter Notebook file, in which:

 -  The  `event_datafile_new.csv` dataset is where all the data is read and processed from the event_data directory to create a denormalized dataset
-   The data tables are created based on the provided queries. 
-   The data is loaded into tables I create in Apache Cassandra and the queries are run to verify the data model created. 



