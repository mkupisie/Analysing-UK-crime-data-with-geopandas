# Working with UK crime data available on https://data.police.uk/data/

**The above website enables to download csv files that provide street-level crime for the selected date range.**
For each selected month, separate file is generated. Downloaded data used in this project includes:
* * - crime type * *
* * - month and year in which the crime occured * *
 - longitude and latitude of the crime event
 - UK counties name in which the crime occured

The purpose of the code is to count the amounts of crime occured in August 2021 in West Midlands in UK for each county and each crime type. 
Shapefile with Local Planning Authorities Boudaries for UK was downloaded from https://geoportal.statistics.gov.uk/ in order to calculate the amounts of crime that occured in each county. Results are presented on interactive map and plot.

Based on the given example of processing crime data for West Midland, function was created to enable to quickly create DataFrame with calculated amount of crime per each West Midlands county for the downloaded csv file for selected month and year.

**Planned extension: extend the function to enable the user to select the counties and upload population data in order to calculate crime rate and show the results on interactive map.
