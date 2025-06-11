Data for the Customer Address by Store Heat Maps

ZIP code geojson data from here:
https://www2.census.gov/geo/tiger/TIGER2024/ZCTA520/

Using this site to extract data for individual states (b/c the entire file is too big to even upload to github as a ZIP):
https://mapshaper.org/

Extraction commands for Mapshaper.org (per ChatGPT, before ban):
-filter'parseInt(ZCTA5CE20) >= X && parseInt(ZCTA5CE20) <= Y

Where X & Y are the upper and lower bounds of ZIP codes for the respective state
