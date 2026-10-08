# Mt. Bierstadt Trail Map

## About the Map
This map displays the Mt. Bierstadt trail in Colorado from the trailhead to the summit. The map was created as part of a web mapping class lab project and is designed to provide an interactive overview of the route, with important markers along the way. The hike up Mt. Bierstadt is over 7 miles long and has almost 3,000 feet of elevation gain. It is considered one of the easier and more accessable Colorado 14ers (mountain summits over 14,000 ft. elevation) and is a great 14er to begin with if you are interested in getting into the hobby. However, be warned that it is still a difficult hike with risks and hazards due to the incredibly high elevation.

## Map Features
The web map includes:

- The Mt. Bierstadt hiking route from the trailhead to the summit
- Markers showing important information along the route
- An interactive Leaflet basemap
- A route line created from GPX data

## Methods
The web map was created using HTML, CSS, and JavaScript, with the Leaflet JavaScript library used to create the interactive map. The trail route data was created using Google Maps and converted into a GPX track using Maps to GPX. The GPX track was then opened, edited, and exported as a GeoJSON file. That GeoJSON file was then used in the web map as the trail route.

Leaflet was used to display the route and provide the interactive mapping functionality, while HTML and CSS were used to structure and style the web page.

## Data Sources
Trail route data was created using Google Maps and converted to GPX using Maps to GPX. The GPX track was edited and exported in and as GeoJSON for use in the web map.

The basemap is provided through Leaflet.

## Files
- `index.html` – main webpage
- `bierstadt.js` – route line data
