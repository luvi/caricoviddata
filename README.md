# Open sourced Caribbean COVID Case Data

Regionally sourced data on cases in the region, that is used to update case information on caricovidmap.com 

Please note that so far this is not a full list of all the latest case information.


## Casesoverride.csv 

Higher numbers in this file for any particular country will cause an immediate update to the Confirmed Cases count on caricovidmap.com The case numbers in this file do not always reflect the latest case information. For an overview of the latest case information with all sources taken into account, visit caricovidmap.com

### Contributing

You may open a pull request to update casesoverride.csv note that you should only update countries where the final overview on caricovidmap.com is still lower than the current situation. Please also include a link to your sources. For adding countries not in the file, the format is as follows:


Province/State,Country/Region,Lat,Long,Confirmed cases

### To note

For now there is no override file for deaths, and active case
