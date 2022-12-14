# chicago-BLMprotests
    >* 1.Project title (5 points)
       Number of BLM-related arrests in Chicago by ZIP code

    >* 2.Data source used in the map
       1). Arrest data downloaded from the Chicago Data Portal (https://data.cityofchicago.org/Public-Safety/Arrests/dpt3-jri9 Links to an external site.)
       2). Arrests on specific charge(8-4-010-(F): Disorderly Conduct – Assembly > 3Persons/Breach of Peach charge) are collected manually. This data doesn’t have arrest location information. So, I identified the location of each “Disorderly Conduct” arrest by utilizing the Chicago Police Department Arrest Record Search (http://publicsearch1.chicagopolice.org/ Links to an external site.). Finally, I merged the location into the arrest dataset based on CB number. 
    
    >* 3.Strategy for drawing the map
       With the merged final dataset, I geocoded the addresses using the MMQGIS plugin (More specifically, Geocoding in QGIS using KY's online geocoding service). I also added a ZIP code(ZIP Code Tabulation Areas) layer downloaded from US.Census Bureau_TIGER/LineShapefiles.
       Finally, I joined the geocoded addresses to the ZIP code layer using the Join attributes by location (summary) tool.

    >* 4.Motivations for drawing this map
       I am now preparing a paper studying the relationship between Chicago citizens exposed to violent protests(or BLM-related arrests) and their demand for police spending. I think this map can show what parts(i.e., ZIP code) of Chicago were more exposed to such protests. 
