# Mapping Mountain Summits Across North Carolina

## Introduction
The purpose of this project is to explore the distribution of mountain summits throughout North Carolina. I wanted to look at where summits are located, how their elevations vary, and how the number of summits differs between counties. The map author (Megan Clarke) is a GIS and Geography Student at Appalachian State University. This interactive web map was to practice JS code, leaflet, USD, and overall communication of geographic information through web mapping and web design. 

## Map Features
This interactive map uses a choropleth layer to show the number of summits in each county using four shades of green. Mountain summit locations are displayed with colored icons representing three elevation categories: under 2,000 feet, 2,000–4,000 feet, and over 4,000 feet. Users can click on individual summits to view their names and elevations in feet. The map also includes a legend, scale bar, and a descriptive introductory pop-up window that can be closed to explore the map.

## Data Sources and Libraries
The simple interactive map was created using HTML, CSS, and JavaScript, along with Leaflet, Leaflet AJAX, Chroma.js, [Font Awesome](https://fontawesome.com/icons/classic/solid/mountain), [GeoJson.io](https://geojson.io/), jQuery, and the [Leaflet.Dialog plugin](https://leafletjs.com/plugins.html). The base map came from [Leaflet Provider](https://leaflet-extras.github.io/leaflet-providers/preview/). The Summit data came from the [USGS Geographic Names Information System (GNIS)](https://edits.nationalmap.gov/apps/gaz-domestic/public/search/names), and county boundaries were downloaded from [NC OneMap](https://www.nconemap.gov/datasets/NCEM-GIS::north-carolina-state-and-county-boundary-polygons/explore?location=35.173910%2C-79.919073%2C6). 

## Data Limitation
Summit locations were obtained from the USGS Geographic Names Information System (GNIS) Domestic Names Search. The original download contained 2,000 summit records, while the search returned 2,729 matching records. Therefore, the dataset represents a partial collection of North Carolina summits rather than a complete inventory. Elevation values are approximate and should be interpreted accordingly.
 