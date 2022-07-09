# Project_two
# ETL Process


##### Team Members: Estela Perez, Paola Moreno, Ramiro Cervantes

##


## Background
The purpose of our project is to historically analyze global inflation rates and their respective national income and unemployment levels, as well as their relation to major world events. 

## Dependencies
* import pandas as pd
* from sqlalchemy import create_engine
* from sqlalchemy.inspection import inspect
* from config import username, password, host, port, protocol

# ETL PROCESS

## EXTRACT
During the data extraction phase, we exported both structured and unstructured raw data from various source locations to our staging area. 
### Sources

Global Annual Inflation Dataset
Source: Data.World
(https://data.world/johnsnowlabs/annual-inflation-by-gdp-deflator)


U.S. Inflation History Dataset
Source: These data were scraped from The Balance’s article, “US Inflation Rate by Year From 1929 to 2023”
(https://www.thebalance.com/u-s-inflation-rate-history-by-year-and-forecast-3306093)

U.S. Monthly CPI Dataset
Source: Kaggle
(https://www.kaggle.com/datasets/neelgajare/usa-cpi-inflation-from-19132022)


Unemployment Dataset
Source: Kaggle
(https://www.kaggle.com/datasets/prasertk/inflation-interest-and-unemployment-rate)

Income Dataset
Source: These data were pulled from the World Bank Databank; Wolrd Development Indicators.
(https://databank.worldbank.org/source/world-development-indicators#)

### Initial Process

In the initial phase we imported dependencies, which allowed us to extract, transform, and load our data into our notebook. We imported “pandas” for extracting the data from CSV files and a website into data frames with read function, for transforming and cleaning it. From SQLAlchemy we imported functions such as “create-engine” and “inspect”, which connected our notebook to Postgresql database and its tables, thus allowing us to import clean data into it.

### Reading the CSVs

For most of our datasets, we were able to use a simple pandas.read to load our CSV files into a Jupyter notebook. Example below.

 






## Visual of Web Application

![alt text](Mission_to_Mars/final_application_screenshot.png)





  
