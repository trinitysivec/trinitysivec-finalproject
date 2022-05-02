# GEOG 4046 Final Project - Trinity Sivec
Three geographic web sources centered in Johnstown, PA.

## Story Map URL
https://lsu-its.maps.arcgis.com/apps/MapTour/index.html?appid=fbc30cb30085461286fec762048dc8e5
This story map follows 5 different locations in Johnstown, PA. The first location is the South Fork Dam, which was the source of the 1889 Johnstown Flood. The other 4 sources are other dams/reservoirs in the Johnstown area that may serve as potential flood sources.

## Instant App URL
https://lsu-its.maps.arcgis.com/apps/instant/minimalist/index.html?appid=3f37a386d9744c4299d5536224376721
This Instant App utilizes 2 layers. The first is a polygon feature layer made using GeoJSON. It contains polygons that mark the shape and location of the 4 reservoirs described in the story map.

## Google Earth Image Analysis URL

https://code.earthengine.google.com/?accept_repo=users/trinitysivec/elevationexplorer

This is an elevation explorer centered in Johnstown, PA. It can be utilized with this project because as you click on the map, an output with the elevation and slop of that area appears. Individuals can use this link to further determine whether their location in Johnstown is a potential flood zone or located near one.

## Project Description
For the story map, I used Google Earth to collect the latitude and longitude of each flood source location. I also used this to determine the elevation of each flood source, as this is a pretty mountainous area of Pennsylvania. Then, I created a .csv file in Excel and export names, values and descriptions of each flood source. Using the StoryMap builder by esri, I uploaded the .csv file to showcase each location. For the Instant App, I used the polygon layer from the StoryMap and put another layer on top named US Flood Hazard Areas. I got this layer from the Living Atlas Layer database on ArcGIS. For the final link, which is an elevation explorer hosted on Google Earth, it was the same code from assignment 9. I included it because it is already centered in Johnstown and anyone can check their location in the town to see their current elevation. 
