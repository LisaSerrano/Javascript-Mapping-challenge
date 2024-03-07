 # USGS Earthquake Visualization

## Background
The United States Geological Survey (USGS) collects a massive amount of earthquake data from all over the world each day. However, they lack a meaningful way of displaying this data. This challenge aims to develop a visualization tool to help the USGS better educate the public and other government organizations about issues facing our planet.

## Part 1: Create the Earthquake Visualization
Your first task is to visualize an earthquake dataset. Follow these steps:

1. Get your dataset: Visit the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and choose a dataset to visualize.

2. Import and visualize the data: 
   - Use Leaflet to create a map that plots all the earthquakes from your chosen dataset based on their longitude and latitude.
   - Reflect the magnitude of the earthquake by the size of the data markers and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
   - Include popups that provide additional information about each earthquake when its associated marker is clicked.
   - Create a legend to provide context for your map data.

## Part 2: Gather and Plot More Data (Optional)
Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. Follow these optional tasks:
- Pull in the tectonic plates dataset from [fraxen/tectonicplates](https://github.com/fraxen/tectonicplates).
- Plot the tectonic plates dataset on the map in addition to the earthquakes.
- Add other base maps to choose from.
- Put each dataset into separate overlays that can be turned on and off independently.
- Add layer controls to your map.

This part is optional and can be completed as a way to challenge yourself and boost your skills.

## Submission
Submit your completed visualization tool along with any optional enhancements you've implemented. Ensure your repository has regular commits and a thorough README.md file.
