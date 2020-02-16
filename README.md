# police-data
This folder contains the data used to analyze trends in police shootings/killings by police. Four databases were obtained to evaluate these trends:
1. [Fatal Encounters Database](https://fatalencounters.org/)
2. [Washington Post Fatal Force Database](https://github.com/washingtonpost/data-police-shootings/blob/master/fatal-police-shootings-data.csv)
3. [Mapping Police Violence Database](https://mappingpoliceviolence.org/s/MPVDatasetDownload.xlsx)
4. An expanded Police Shootings Database was constructed that includes the total number of police shootings incidents, both fatal and non-fatal, from 2013-2019 as reported by the 30 largest US city police agencies via their Data Dashboard/Open Data Portals and documents published online via public records request.

Variables used in the analysis include:
- *Agency* - the law enforcement agenc(ies) involved in each incident. Since agency info was not included in the WaPo database, agency info was added using the "WaPo ID number" column within the Mapping Police Violence database. 
- *30 Largest City Agencies* - a variable that identifies whether the police agency involved was the primary law enforcement agency of one of America's 30 largest cities, according to [2018 ACS Population Estimates](https://data.census.gov/cedsci/table?q=United%20States&g=0100000US.160000&tid=ACSDT1Y2018.B01003&hidePreview=true)
- *Date of Incident* - used to determine the number of incidents per year.
- *Geography* - Geographies of police killings were identified as urban, suburban, or rural based on the population density of each incident's zipcode, using the [methodology established by Trulia](http://jedkolko.com/wp-content/uploads/2015/05/full-ZCTA-urban-suburban-rural-classification.xlsx)
- *Arrests* data were obtained via the 2013-2018 FBI Uniform Crime Reports as listed on the [FBI's Crime Data Explorer website.](https://crime-data-explorer.fr.cloud.gov/explorer/national/united-states/arrest)
