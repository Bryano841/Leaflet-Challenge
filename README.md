# USGS-Earthquake-Analysis

The goal of this project was to use JavaScript to present an interactive map visualization of USGS earthquake data within a web page. Since the baseline data was provided in GeoJSON format, Leaflet was used to import and process the data, as well as generate the required visualization.

## Questions

What are the locations and magnitudes of all earthquake events in the last twenty-four hours?

## Tasks

Import the GeoJSON data.
Extract the location, magnitude, and timestamp of each earthquake event.
For each earthquake event, create a pop-up box with the above information.
For each earthquake event, create a circle marker whose size and color are proportional to the event's magnitude.
Import four map layers (satellite, outdoors, dark, light) from the Mapbox API.
Link the map layers, circle markers, and pop-up boxes together to create the interactive map.
Create a legend for the circle marker color scale and add it to the interactive map.
