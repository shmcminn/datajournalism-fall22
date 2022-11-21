# Air quality 2022 analysis

NPR story from 2020 https://www.npr.org/2020/09/23/915723316/1-in-7-americans-have-experienced-dangerous-air-quality-due-to-wildfires-this-ye

Outcome:

* Map showing max AQI reading per county
* Map showing number of very unhealthy days per county 
* Stacked bar chart showing number of people who experienced unhealthy/very unhealthy/hazardous days by state

Steps:

1. Combine CA/OR/WA data
1. Create FIPS
1. Pivot to get column for each date and row for each FIPS code
1. Count the number of unhealthy/very unhealthy/hazardous for each county
1. Calculate the "worst" AQI status per county
1. Open CSV and shpfile in QGIS  
1. Merge CSV and shpfile in QGIS
1. Create maps
1. Open population CSV in QGIS 
1. Merge population CSV with shpfile in QGIS
1. Export CSV from shpfile in QGIS 
1. Pivot table in Excel to calculate the number of people in each state by "worst" experienced
1. Chart stacked bar by state in Datawrapper