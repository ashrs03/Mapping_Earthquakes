# Mapping Earthquakes

## Overview of Project

The task delegated is for creating interactive maps using GeoJSON data for data driven story telling. Insightful data vidualizations were worked upon on earthquakes all around the world. Using earthquake maps useful and available on desktop and mobile phones is intended to create positive marketing presence for disaster reporting tools. 

Javascript, D3 and leaflet libraries were used along with mapbox maps.  Earthquake diameters is reflected with the size and color to show earthquakes which are larger/ smaller with certain colors as per the legend.

The project involved showing earthquakes of different magnitudes all over the world for the last seven days. URLs for GeoJSON earthquake data, and GeoJSON major earthquake data from the USGS website was added as overlay and to this its relation to tectonic plates location on earth was added. 

## Analysis 
Once tectonic plata data (GeoJSON) is called from d3.json the tectonic layer group variable is added and the details are filled in to display the street and satellite view of the map. Next step was to add major earthquake data to map using d3.json(). After this color and radius of the circle markers are set based on the magnitude of earthquake, and popup marker for each earthquake is added that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().
The three layers added are Tectonic Plates, Earthquakes and Major Earthquakes. The map styles added are Street, Satellite and Dark 

All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off. 

## Summary 
The earthquake data can be visualized and a story presented on the same based on the selection of layers and the map styles. 
The following images summarize visually on earthquake data across the world using different variable sof layers and map style 

<img width="960" alt="Street-1" src="https://user-images.githubusercontent.com/42523379/210124664-ca3809dd-36c4-4e14-bb77-8e97e2d12e13.png">

<img width="957" alt="Satellite-1" src="https://user-images.githubusercontent.com/42523379/210124671-1772b477-5579-4610-b4c5-b41c6d664c38.png">

<img width="959" alt="Dark-1" src="https://user-images.githubusercontent.com/42523379/210124676-eccc7cff-59e4-4322-be36-b946006a4867.png">

<img width="958" alt="Street-Earthquakes-Tectonics" src="https://user-images.githubusercontent.com/42523379/210124678-33248398-747b-463e-a06d-66e54b922807.png">

<img width="958" alt="Satellite-Earthquake-Tectonics" src="https://user-images.githubusercontent.com/42523379/210124680-67178426-7b80-4208-9ef0-ea9bf044305d.png">

<img width="957" alt="Dark-Tectonics-Majorearthquakes" src="https://user-images.githubusercontent.com/42523379/210124683-2368e763-451a-427a-a6de-b52a9c261566.png">


