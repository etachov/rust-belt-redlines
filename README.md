# Rust Belt Redlines

The goal of this project was to layer current income data on top of HOLC maps from the 1930s and 1940 to take a look at the legacy of redlining in Cleveland, Chicago and Detroit. The final maps were published in [Belt Magazine](http://beltmag.com/the-legacy-of-redlining-in-rust-belt-cities/) and picked up by [CityLab](http://www.citylab.com/housing/2015/03/mapping-the-lasting-effects-of-redlining/388333/)

The original maps Chicago and Detroit maps were downloaded from [urbanoasis.org](http://urbanoasis.org/) and the Cleveland map was downloaded from The Ohio State University Library's [collection](http://library.osu.edu/find/collections/maps/redlining-maps-ohio/). Census data was downloaded from the American Commmunity Fact Finder site. 

The original raster maps were georeferenced using QGIS and the Census data was merged with the shapefiles using R. The final maps were created with Mapbox's Tilemill. 

The georeferenced .tif files are available for download [here](https://www.dropbox.com/sh/bgazkmclgnq97ru/AAAHxO87UYY4nWmNcJaJG9Rca?dl=0). **Warning: the tif files are pretty big**.