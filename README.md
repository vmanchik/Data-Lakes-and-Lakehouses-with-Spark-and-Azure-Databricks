# Data Lakehouse for Divvy Bikeshare with Spark and Azure Databricks

Divvy is a bikeshare service in Chicago. It provides an easy and affordable way to explore the city by renting classic bikes, e-bikes, or scooters via an app. The company offers unlimited 45-minute rides on classic bikes and premium Lyft Pink membership. More information can be found on their [website](https://divvybikes.com).
As part of Udacity's course on Data lakes and Lakehouses with Spark and Azure Databricks, we developed a data lakehouse solution for Divvy by set up an ELT pipeline to extract, load and transform Divvy's data in order to to answer questions critical co company's business outcomes.

## The business outcomes:
1. Analyze how much time is spent per ride
 - Based on date and time factors such as day of week and time of day
 - Based on which station is the starting and / or ending station
 - Based on age of the rider at time of the ride
 - Based on whether the rider is a member or a casual rider
2) Analyze how much money is spent
 - Per month, quarter, year
 - Per member, based on the age of the rider at account start
 - Per member based on how many rides the rider averages per month
 - Per member based on how many minutes the rider spends on a bike per month

## Data

The City of Chicago makes the anonymized bike trip data publicly available for projects, which we used in this project at part of the course assignment.  Below is information more information on the structure of the raw data.

