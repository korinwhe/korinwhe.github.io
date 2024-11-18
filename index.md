---
layout: default
---

# Korin's projects

# Intro to Data Science projects
This section primarily includes projects from _Intro to Data Science_

## Data Sources and Project Ideas
Here are the data sources or project ideas that I would like to use for the Intro to Data Science final
1. Deaths and their causes by state 2020-2023, rate of ER visits
2. Hospitalization, and death caused traumatic brain injury
3. Provisional COVID-19 Deaths: Focus on Ages 0-18 Years
4. Foodborne illnesses at Mcdonalds
5. Sex by age by disability

## Where's Schueller? project
This section's purpose is to embed a **"live"** plotly visualization in my page from your recent analysis of my geolocation data.

# Geolocation Heatmap

This map shows the geolocation data analysis results, including the likely home and farthest traveled point.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Embedded Mapbox Map</title>
    <link href="https://api.mapbox.com/mapbox-gl-js/v2.7.0/mapbox-gl.css" rel="stylesheet">
    <script src="https://api.mapbox.com/mapbox-gl-js/v2.7.0/mapbox-gl.js"></script>
    <style>
        #map { 
            height: 500px; 
            width: 100%;
        }
    </style>
</head>
<body>

    <h1>Embedded Interactive Map</h1>

    <!-- Map container -->
    <div id="map"></div>

    <script>
        mapboxgl.accessToken = 'pk.eyJ1Ijoid2hlYXRvbmsiLCJhIjoiY20zNTIybDNmMDVxZjJrcHk5dTYwc3A2MiJ9.9GCP7xBNggy-1gKw_jLvCw';

        var map = new mapboxgl.Map({
            container: 'https://korinwhe.github.io/_includes/vis.html', // ID of the container element
            style: 'mapbox://styles/mapbox/streets-v11', // Map style
            center: [-74.5, 40], // Longitude and latitude of the center
            zoom: 9 // Zoom level
        });

        // Add navigation controls (optional)
        map.addControl(new mapboxgl.NavigationControl());
    </script>

</body>
</html>




## Above and Beyond
This section is empty right now. Unsure of what to exactly include. 
