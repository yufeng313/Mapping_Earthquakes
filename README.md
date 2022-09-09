# Mapping_Earthquakes
Mapping Earthquakes with JS &amp; APIs
## Overview
The purpose of this project is to visually show the magnitudes of earthquakes and all the earthquakes with a magnitude greater than 4.5 all over the world for the last seven days, and also the earthquake data in relation to the tectonic plates’ location on the earth.

## Resources
Data Source: 
https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson<br/>
https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson<br/>
https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json<br/>
Software: VS Code 1.68.1, HTML/CSS, JavaScript, Leaflet 1.7.1

## Results
### Create the earthquakes map
1.set up a Mapbox account and get the API token you'll need to create geographical maps, create an HTML file and CSS file and add links to some stylesheets in the HTML file, here are some codes below:<br/>
![set up the map](https://user-images.githubusercontent.com/107179765/188703400-c4491f5a-e918-4a23-852e-a6675c0bf0ac.png)<br/>

2.use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data, here are some codes below:<br/>
![use D3 js library witnin JavaScript](https://user-images.githubusercontent.com/107179765/188703444-97befb6e-3c1f-49cb-8016-002a303a01f3.png)<br/>

3.use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data. Here are the base maps below: <br/>
1) streets view<br/>
![streets view](https://user-images.githubusercontent.com/107179765/189293431-7ab82212-d132-45fa-945c-268bf8dcbe70.png)<br/>
2) satellite view<br/>
![satellite view](https://user-images.githubusercontent.com/107179765/188703874-5ce449a4-e0e4-4fc6-9438-97100389aa8e.png)<br/>
3) dark view<br/>
![dark view](https://user-images.githubusercontent.com/107179765/189293514-0a2424b7-432d-4c15-8e30-a9eb00a779cf.png)

## Summary
So far, we have a completed map for showing the magnitudes of earthquakes for the last seven days with major earthquakes data and tectonic plate data being added.
