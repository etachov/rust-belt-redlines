# Rust Belt Redlines

The goal of this project was to layer current income data on top of HOLC maps from the 1930s and 1940 to take a look at the legacy of redlining in Cleveland, Chicago and Detroit. 

The original maps Chicago and Detroit maps were downloaded from [urbanoasis.org](http://urbanoasis.org/) and the Cleveland map was downloaded from The Ohio State University Library's [collection](http://library.osu.edu/find/collections/maps/redlining-maps-ohio/). Census data was downloaded from the American Commmunity Fact Finder site. 

The original raster maps were georeferenced using QGIS and the Census data was merged with the shapefiles using R. The final maps were created with Mapbox's Tilemill. 

<iframe width='100%' height='500px' frameBorder='0' src='https://a.tiles.mapbox.com/v4/thac.lfp9plcj/attribution,zoompan,zoomwheel,geocoder.html?access_token=pk.eyJ1IjoidGhhYyIsImEiOiJtOEgxY1c0In0.R0lZZADkH3i5mGKRgpXw0g'></iframe>