# Leaflet Homework - Visualizing Data with Leaflet

## Visualise data
I removed my API key from the folder so you'll be only to stream the geo layers but not the mapbox tiles.

To visualise first part of the data  click in this [page](https://thawk18.github.io/leaflet-challenge/Leaflet-Step-1/) 
To visualise second part of the data click in this [page](https://thawk18.github.io/leaflet-challenge/Leaflet-Step-2) 

For the full experience, please clone my folder and insert the API key in the config.py file


### Level 1: Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

First task was to visualise the earthquake date of the last week centered in US California. Lots of data able to be seen as this is a highly seismic area. 

1. **Getting data**

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) 'All Earthquakes from the Past 7 Days' was picked to get a json representation of the data.

   ![4-JSON](Images/4-JSON.png)

2. **Visualizing the data**

Data was imported and visualised with using seismic Magnitude (mag) for the circle radius and Depth (coordinate[2]) for the circle colours. A legend was added to colour scale the depth. 


### Level 2: More Data (Optional)

![5-Advanced](Images/5-Advanced.png)

 Data on tectonic plates could be found at <https://github.com/fraxen/tectonicplates>. and integrated additionally to the first visualization

2 x aditional tiles were added with layer control. The layer control was also available for removing or adding the seismic data and the tectonic plates. 

The map was centered around the equatorial GMT coordinates and zoomed out to give us a familiar perspective of the world map. 
