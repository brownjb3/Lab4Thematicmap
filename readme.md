Data
The data for this application comes from US Census Bureau and other public sources. The dataset is in GeoJSON format, which is used to define the geographic locations (states) and the associated data (number of deaths). The dataset includes the following properties:

state: Name of the state.

death: Number of car accident deaths in that state.

The data is loaded into the map using the Leaflet.ajax plugin, and the markers are adjusted based on the values associated with each state.

Symbolization
The map uses circle markers to represent each state's data. The size and color of the circles are based on the number of car accident deaths:

Circle Size: The radius of each circle is proportional to the number of deaths, with larger circles representing higher numbers.

Circle Color: The color of the circles represents the severity, with a color gradient indicating low to high values. By default, the circles are colored red for low values, orange for medium values, and green for high values.

Tooltip
When hovering over a circle, a tooltip appears, displaying the following information:

State: The name of the state.

Deaths: The number of deaths attributed to car accidents in that state.

Design
The map takes up the full screen

The title is placed at the top left with a blue background

The map is interactive

Technologies
This application uses the following technologies:

Leaflet.js: A JavaScript library for creating interactive maps.

Leaflet.ajax: A Leaflet plugin that helps load GeoJSON data asynchronously.

GeoJSON: A format used to encode geographic data structures.

HTML/CSS: For structuring and styling the webpage.

JavaScript: For dynamic functionality and data visualization.