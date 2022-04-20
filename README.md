# geomaroc
Python library to make working with geospatial data of Morocco easier
![geomaroc_logo](https://user-images.githubusercontent.com/49843367/164335838-537f0514-ce89-43ed-956f-c6c6de6ed264.png)

People who work in data science are seeing  increased need to work with geospatial data, especially for visualization purposes (e.g. during the covid-19 pandemic).Geopandas is a very popular geospatial library in python that extends Pandas to allow spatial operations on geometrics types.

Working with geopands requires having access to coordinates of the items of our map (polygon coordinates), which is not an easy task.In fact, we often need the shapefiles of the map we are looking to plot. Trying to find those shapefiles can be a long journey especailly for someone with zero experience with geospatial. Moreover, for someone interested in geospatial data of Morocco, the majority of shapefiles available online are of very poor quality and they don't provid province-level,prefectue-level or district-level coordinates.

Geomaroc helps the user get those coordinates easly.In addition, it provides the coordinates to plot regions, provinces and districts/cercles of morocco.
