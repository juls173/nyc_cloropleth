# NYC Traffic Density and Air Pollution Cloropleth Maps
Visualization of NYC Community District level data on air pollution (pm and vehicle miles driven (million miles per km^2). 

Air pollution & traffic density data sourced from: https://opendata.cityofnewyork.us/
Community district shapefiles from: https://data.cityofnewyork.us/City-Government/Community-Districts/yfnk-k7r4
As the CDs are named and indexed differently in these two files, I manually matched up their indices when cleaning the data.

libraries used:
- pandas
- geopandas
- matplotlib
- zipfile to extract shapefile file from .zip
