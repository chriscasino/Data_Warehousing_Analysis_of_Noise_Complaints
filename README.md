# Data Warehousing Analysis of Noise Complaints

###### In this project, we wish to detect whether there is a correlation between temperature and 311 Complaints reported in New York City. 

* We will analyze two different datasets: “311_Service_Requests_from_2010_to_Present” and “weather_data_5_boroughs_daily”, both of which are .csv files. 
* It should be noted that the “weather_data_5_boroughs_daily” dataset was provided to us, while the data in “311_Service_Requests_from_2010_to_Present” was filtered from NYC OpenData using the Socratica API. 

* Link to 311 Service Requests from 2010 to Present: https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/data


## With the two datasets, we have mapped the following KPIs:

* Number of “Residential” Noise complaints per day/month
* Number of “Commercial” Noise complaints per day/month
* Number of Complaints per Complaint Type
* Average temperature per month
* Average temperature at location/borough

## Procedure:
1. Identify the two datasets to be used for analysis
2. Create Dimensional Models for both datasets
3. Create the Integrated Warehouse Model for both datasets to be used in the analysis
4. Write scripts in Python to clean data of N/A values and duplicates, and load data into Google Big Query 
5. Create queries in Google Big Query to measure APIs
6. Visualize findings of analysis using Tableau


###### Citation:
###### DoITT, & 311. (2011, October 10). 311 service requests from 2010 to present: NYC Open Data. 311 Service Requests from 2010 to Present | NYC Open Data. Retrieved December 10, 2022, from https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9 

