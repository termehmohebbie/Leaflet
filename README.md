# Leaflet-challenge
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

In this challenge, we are developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## part 1: Create the Earthquake Visualization

In this part we want to visualize an earthquake dataset. To do so, we used an API from http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php which gives us a JSON representation of earthquakes data from the past 7 days. Then we created a leaflet map and plot the JSON file based on their longitude and latitude.


![2-BasicMap](https://user-images.githubusercontent.com/114199979/221996506-aed920d7-4fb3-404b-8c55-a11aa5de1a10.jpg)

## Part 2: Gather and Plot More Data

In this part we tried to plot a second dataset on the map to illustrate the relationship between tectonic plates and seismic activity. We pulled in this dataset and visualized it alongside the original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates 

![5-Advanced](https://user-images.githubusercontent.com/114199979/221997267-fb348eb7-d80d-4fa1-987a-a7c8395ef76c.jpg)

