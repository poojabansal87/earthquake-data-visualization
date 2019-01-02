# earthquake-data-visualization
Earthquake Data Visualization using Leaflet.js

## Background

In this project, I have created a visualization of earthquake data from USGS using Leaflet.js.

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. 

The project aims to visualize this data in a way which will allow the USGS team to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

1. **Getting the dataset**

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. I got the dataset on [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and picked a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. I used the URL of this JSON to pull in the data for visualization.

2. **Import & Visualize the Data**

   The map was created using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

   * The data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color.

   * When a marker is clicked, popups appear that provide additional information about the earthquake.

- - -