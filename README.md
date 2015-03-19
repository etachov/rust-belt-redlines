# Rust Belt Redlines

The goal of this project was to layer current income data on top of HOLC maps to take a look at the legacy of redlining in three Rust Belt cities, Cleveland, Chicago and Detroit. 

The original maps Chicago and Detroit maps were downloaded from urbanoasis.org and the Cleveland map was downloaded from The Ohio State University library system. Census data was downloaded from the American Commmunity Fact Finder site. 

The original raster maps were georeferenced using QGIS and the Census data was merged with the shapefiles using R. The final maps were created with Mapbox's Tilemill. 