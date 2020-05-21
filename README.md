# Mapping Earthquakes

Building insightful visualizations with interactive features on earthquakes from around the world. Using Javascript, and the D3 and Leaflet libraries:

1. Traverse and retrieve the earthquake data.
2. Retrieve tectonic plates data.
3. Plot the data on a mapbox map through an API request.

## Resources

  - Data Source: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson , https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
  - Software: Visual Studio Code 1.43.0, HTML, CSS, JavaScript (ES6), Mapbox
  - Libraries: D3.js, Leaflet.js

## Recognition

The tectonic plates data was retrieved from the following GitHub Repository: https://github.com/fraxen/tectonicplates. As well, I would like to give credit and recognition to the following for the wonderful resource: Hugo Ahlenius, Nordpil and Peter Bird. All original data were retrieved from http://peterbird.name/oldFTP/PB2002/.

## Summary

![](https://github.com/Helen-Ly/Mapping_Earthquakes/blob/master/Earthquake%20and%20Tectonic%20Plates%20Map.png)

As we see in the map, we have plotted both the earthquake and tectonic plates data. We picked colours that would be visible for each map option. The size and colour of the circle markers corresponds to the magnitude of the earthquake. We have also included a legend to provide context for our mapped data. Aside from choosing which map you want to view the data, you can also choose which data to view. Both the earthquake and tectonic plates data are overlays and can be turned off. These choices are located at the top right of the map. Toggle over the icon to select your options.

The finished product is within the *Earthquake_Challenge* folder. However, if you would like to see each step of the process or how to create specific features, you can take a look at the other folders or branches.

## Usage

**Note:** Please ensure you have all the required and updated softwares on your computer.

  1. Download the following folder for the project.
      
      - Earthquake_Challenge folder

  2. Open Visual Studio Code from your project's folder.

  3. Open the index.html in your browser.

  4. Toggle over the icon at the top right to select your map and overlay options.
