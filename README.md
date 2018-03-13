# geospatial
Exploration of Geo-spatial concepts

Operations on shapefiles using geopandas, plotting shapefiles with annotation and creation of a heatmap using Colorado Oil Well production data for the year 2017.

## OilAndGasMap.ipynb

Python notebook illustrating the use of geopandas and shapely libraries 
to draw maps and explore geospatial concepts.  The notebook shows how to read a shapefile and plot it,
plot arbitrary points on a map, create a map with layers and produce a heat map.  The notebook uses real data
from the Colorado Oil & Gas Conservation Commission to show the position of 2017 crude oil production relative
to Colorado’s population centers.

The notebook references shapefiles and oil well production data.
These data items are supplied in the `data.zip` file in the repo.
Download this file and unzip it to directory in which you'll run the notebook.
Unzip will create the `data` directory that the notebook requires.
The shapefiles are from the US Census Bureau and
[Colorado Information Marketplace](https://data.colorado.gov/Municipal/Municipal-Boundaries-in-Colorado/u943-ics6/data)
Oil well production data is from the Colorado Oil and Gas Conservation Commission.

## OilWellAge.ipnb (in progress)

Exploration of the relationship between the age of an oil well and its output