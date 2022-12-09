# Udacity Data Enginering nanodegree capstone poject
### U.S city average temperature and Immigration data Data Lake

#### Project Summary
Generally the scope of this project is to model the data lake allowing users to capture and visualise the changeof ground tempratures throught out the years, now i have chosen to includetemperatures measured even before commercial airtravel was introduced.

We will attempt read, write and analyise data for more than 200k+ travelers
using spark for our U.S immigration data provided by the US National Tourism
and Trade Office, residing on a github repository as well as the World Temperature Data found on kaggle, U.S. City Demographic Data from OpenSoft and finally, U.S Airport Code Table data.

links for the data sources all provided in the last cell.

Deploying a star schema database desing as the immigration data is the fact table vs
the national temprature readings table, the national land air and sea ports table, 
the us city demographics table as dimension tables, and finally a time table extracted from
our immigration data
