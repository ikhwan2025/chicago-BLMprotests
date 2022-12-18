# BLM-related protests by Chicago ZIP Code
<ul>
	<li>See my map: <a href="https://ikhwan2025.github.io/chicago-BLMprotests/">BLM-related protests</a></li>

<!-- /TOC -->

## Descriptions

This map illustrates BLM-related arrests (Numbers and locations) by Chicago ZIP code during two major waves of 2020 Chicago BLM protests. I have identified via different sources of news that there were two major waves of BLM protests in 2020 at Chicago (May 30 – June 2 and August 9-August 10). To capture only BLM-related arrests, I use arrests on 8-4-010-(F) Disorderly Conduct-Assembly>3 Persons/Breach of Peace charge.

There are two reasons why I think those (F) type arrests can capture BLM-related arrests. First, most of the F-type arrests in 2020 were concentrated in those two periods. Specifically, the total number of F-type arrests in 2020 is 808, and 788 F-type arrests occurred during either May 30 – June 2 or August 9-August 10. Secondly, I have found that the Chicago Police Department used this F-type charge almost exclusively in 2020 during those two periods. As mentioned earlier, there were 788 F-type arrests during either May 30 – June 2 or August 9-August 10. However, there was only one F-type arrest in 2019 and two in 2021. 

<!-- /TOC -->

## Motivations for drawing this map
I am now preparing a paper studying the relationship between Chicago citizens exposed to violent protests (or BLM-related arrests) and their demand for police spending. I think this map can show what parts (i.e., ZIP code) of Chicago were more exposed to such extreme protests (or arrests).

## Strategy for drawing this map
1. For this purpose, I have downloaded the arrest data from the Chicago Data Portal. Then, I collected arrests on a specific charge, which is 8-4-010-(F): Disorderly Conduct – Assembly > 3Persons/Breach of Peach charge. This dataset doesn’t’ have arrest location information. So, I identified the location of each “Disorderly Conduct” arrest by utilizing the Chicago Police Department Arrest Record Search. I merged the location into the arrest dataset based on CB number. I would like to note that the Chicago Police Department issues a "CB" (Central Booking) number to arrestees for identification purposes. 

2. With the merged final dataset, I geocoded the addresses using the MMQGIS plugin (More specifically, Geocoding in QGIS using KY's online geocoding service). I also added a ZIP code (ZIP Code Tabulation Areas) layer downloaded from US. Census Bureau. Finally, I joined the geocoded addresses to the ZIP code layer using the Join attributes by location (summary) tool.  

<!-- /TOC -->

## Conclusion and Takeaway
Of all the 58 ZIP code areas relevant to Chicago, 19 ZIP code areas experienced no BLM-related arrests during two major waves of 2020 Chicago BLM protests. However, such arrests were made at 39 ZIP code areas. Four ZIP code areas (60601, 60602, 60603, 60611) had at least one BLM-related arrest during both two waves. In conclusion, we can know that BLM-related arrests were not made at the far north side and far southeast side of Chicago. Moreover, the central side of Chicago experienced such arrest during both two major waves. 


## Map Data 
*Chicago Arrest data: https://data.cityofchicago.org/Public-Safety/Arrests/dpt3-jri9 

*Chicago Police Department Arrest Record Search: http://publicsearch1.chicagopolice.org

*ZIP code outline data: https://www.census.gov/cgi-bin/geo/shapefiles/index.php

<<<<<<< HEAD
=======
<ul>
	<li>See my map: <a href="https://ikhwan2025.github.io/chicago-BLMprotests/">BLM-related protests</a></li>
<<<<<<< HEAD
>>>>>>> 28725e3ab9b27f25babc3ec4e45fcf6252ec8a84
=======
>>>>>>> 28725e3ab9b27f25babc3ec4e45fcf6252ec8a84
