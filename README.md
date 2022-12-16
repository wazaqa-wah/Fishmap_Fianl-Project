# Final Project
This projects aims to look at the fish population for the entire Hudson River. The dataset used is from [National Oceanic and Atmospheric Administration (NOAA)'s Sensitivity of Coastal Environments and Wildlife to Spilled Oil: Hudson River](https://www.fisheries.noaa.gov/inport/item/40343). This fish dataset is chosen specifically because it not only shows the beautiful shape of the Hudson River, but it's also of interest to the author since she has pet fishes since she was a kid. The map shows sensitive biological resource data for marine, estuarine, anadromous, and freshwater fish species in the Hudson River, as well as their species-specific abundance, seasonality, status, life history, and source information. For the purpose of this projects, only the basic information of the fishes is being utilized.

## Built with
* D3.js
* Leaflet
* Bootstrap

## Features
* The site has only one page, with the map component on the left side and a simple sidebar on the right for fish information.
![This image shows the front page of the map, with a leaflet map on the left containing the fish polyons and a side bar on the right](https://github.com/wazaqa-wah/Fishmap_Fianl-Project/blob/main/site_1.png "Front page of the site")
* This image shows the webstie when you first open it up. The Hudson River has been divided into polygons and each polygons were colored differently for the audiences to explore. Under the page title insturctions were written so that users understand how to use this page. When hover over the polygon, a tooltip shows up containing the number of fish species in this water body, as well a prompt for user to click on it. Once the user hover off the polygon, the color of the polygon will turn to blue, indicating they have already checked it out. An "About" button is at the bottom of the sidebar so users can briefly learn about the purpose of the project as well as the dataset being used.

![This image shows site after you click on it, with the sidebar updating fish information in the water polygon](https://github.com/wazaqa-wah/Fishmap_Fianl-Project/blob/main/site_2.png "Site with sidebar displaying fish info")
* This image shows the website after users click on the polygon. The sidebar on the right now displays all the fish as well as their basic information in the water body of the user's choice. All the name of the fishes are linked to their wikipedia page, allowing users to learn more. 

## Code References
* [Fixing GeoJSON format](https://stackoverflow.com/questions/49311001/d3-js-drawing-geojson-incorrectly)
* [Layer GeoJSON on Leaflet map](https://observablehq.com/@pbogden/d3-leaflet-tooltip)
