# US Census Tracts as Tables
Conversion of US Census Tiger Line files for each tract and converted the features into tabular data.

Sources
2016 FIPS Codes
https://www.census.gov/geographies/reference-files/2016/demo/popest/2016-fips.html

2019 TIGER/Line® Shapefiles: Census Tracts
https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2019&layergroup=Census+Tracts

## Column Definitions
https://www2.census.gov/geo/pdfs/maps-data/data/tiger/tgrshp2019/TGRSHP2019_TechDoc.pdf (jump to section 3.4.1)

STATEFP = state FIPS code
COUNTYFP = county FIPS code
TRACTCE = census tract code
GEOID = Census tract identifier; a concatenation of Current state FIPS code, county FIPS code, and census tract code
NAME = Current census tract name, this is the census tract code converted to an integer or integer plus 2- character decimal if the last two characters of the code are not both zeros.
NAMELSAD = translated legal/statistical area description and the census tract name
MTFCC = MAF/TIGER feature class code (G5020)
FUNCSTAT = functional status
ALAND = land area
AWATER = water area
INTPTLAT = latitude of the internal point
INTPTLON = longitude of the internal point


## Helpful Others

ACS + Tigerline 
https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-data.html

Explainer on GeoIDs
https://www.census.gov/programs-surveys/geography/guidance/geo-identifiers.html

HUD USPS Zip Code Crosswalk Files
https://www.huduser.gov/portal/datasets/usps_crosswalk.html

I don't know what this is
https://www.census.gov/geographies/reference-maps/2010/geo/2010-census-tract-maps.html

Google Sheets Based Geocoder
https://datavizforall.org/geocode.html

Texas A&M Geocoding Servcies
https://geoservices.tamu.edu/Services/Geocode/

FCC
https://geo.fcc.gov/api/census/

US Census Geocode Search + How To Guide
https://geocoding.geo.census.gov/geocoder/geographies/coordinates?form
https://www2.census.gov/geo/pdfs/maps-data/data/FAQ_for_Census_Bureau_Public_Geocoder.pdf?
