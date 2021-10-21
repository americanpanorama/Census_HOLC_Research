# Census_HOLC_Research
 Census boundary crosswalk with HOLC Polygons


This [ArcGIS Pro Toolbox](https://urichmond.maps.arcgis.com/home/item.html?id=45dd0853a6664a469c1770bcd1a20e31) and Python script allows you to crosswalk any Census boundaries (County, Tract, Block) with the Home Owner's Loan Corporation Polygons for reasearch analysis. This tool cuts the Census boundaries to the HOLC polygons and calculates a percent of that boundary that falls within the HOLC neighborhood. Assuming equal distribution you can use this percentage to proportion the variable of choice into the graded neighborhood. Below are the field you will need to populate:

Census Boundaries: Any geospatial census boundaries. Make sure these have a geoid, fips, or nhgis join code. This is used in the dissolve analysis. 
HOLC Polygons: This works best with the DSL's Mapping Inequality HOLC Polygons layer. You will need the holc_grade and neighborhood_id field. 

*Note: This tool with work with any boundary, it does not have to be Census boundaries. The main element you will need is a unique id for each boundary polygon. This can be in place of the geoid, fips, or nhgis join code.

Questions? 
Contact: [Justin Madron] (jmadron@richmond.edu)
 
