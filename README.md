# BLM-related protests by Chicago ZIP Code

<!-- /TOC -->

## Descriptions

This map illustrates BLM-related arrests (Numbers and locations) by Chicago ZIP code during two major waves of 2020 Chicago BLM protests. I have identified via different sources of news that there were two major waves of BLM protests in 2020 at Chicago (May 30 – June 2 and August 9-August 10). To capture only BLM-related arrests, I use arrests on 8-4-010-(F) Disorderly Conduct-Assembly>3 Persons/Breach of Peace charge.

<!-- /TOC -->

## Motivations for drawing this map
I am now preparing a paper studying the relationship between Chicago citizens exposed to violent protests (or BLM-related arrests) and their demand for police spending. I think this map can show what parts (i.e., ZIP code) of Chicago were more exposed to such extreme protests (or arrests).

## Strategy for drawing this map
For this purpose, I have downloaded the arrest data from the Chicago Data Portal. Then, I collected arrests on a specific charge, which is 8-4-010-(F): Disorderly Conduct – Assembly > 3Persons/Breach of Peach charge. This dataset doesn’t’ have arrest location information. So, I identified the location of each “Disorderly Conduct” arrest by utilizing the Chicago Police Department Arrest Record Search. I merged the location into the arrest dataset based on CB number. I would like to note that the Chicago Police Department issues a "CB" (Central Booking) number to arrestees for identification purposes. With the merged final dataset, I geocoded the addresses using the MMQGIS plugin (More specifically, Geocoding in QGIS using KY's online geocoding service). I also added a ZIP code (ZIP Code Tabulation Areas) layer downloaded from US. Census Bureau.  


<!-- /TOC -->

## Map Data 
*Chicago Arrest data: https://data.cityofchicago.org/Public-Safety/Arrests/dpt3-jri9 

*Chicago Police Department Arrest Record Search: http://publicsearch1.chicagopolice.org

*ZIP code outline data: https://www.census.gov/cgi-bin/geo/shapefiles/index.php