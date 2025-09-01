---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Postdoctoral Research Fellow in the Boston University Clinical HIV/AIDS Research Training Program at Boston Medical Center. I earned my PhD in Biostatistics from Boston University, where my doctoral work focused on developing statistical methods to better understand tuberculosis (TB) disease dynamics among key populations. My current work focuses on developing and applying diverse modeling techniques to study TB transmission.
## Research Interests  
My research sits at the intersection of **biostatistics**, **infectious disease epidemiology**, and **global health**. I am particularly interested in:  
- Developing **statistical methods** for **integrating diverse data sources**, including genomic, clinical, and surveillance data.  
- Applying **modeling techniques** such as phylodynamics and mathematical models to understand the spread of infectious diseases.  
- Using these methods to study **tuberculosis** and other pathogens, with the goal of informing prevention and control strategies.
  
## 🌍 Sharing Research Across the Globe

<div id="talks-map" style="height: 400px;"></div>

<!-- Leaflet CSS & JS -->
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<script>
  var map = L.map('talks-map');
  L.tileLayer('https://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}{r}.png', {
      attribution: '&copy; OpenStreetMap &copy; CARTO',
      subdomains: 'abcd',
      maxZoom: 19
  }).addTo(map);

  var talks = [
    { lat: 42.3601, lon: -71.0589, conference: "New England Statistics Symposium", date: "June 2022" },
    { lat: 48.864716, lon: 2.349014, conference: "The Union World Conference on Lung Health", date: "November 2023" },
    { lat: 55.6761, lon: 12.5683, conference: "The Union World Conference on Lung Health", date: "November 2025" },
    { lat: -33.9221, lon: 18.4231, conference: "Stellenbosch University", date: "July 2022" },
    { lat: 33.7490, lon: -84.3880, conference: "MIDAS Network Annual Meeting", date: "July 2022" },
    { lat: 39.29, lon: -76.61, conference: "ENAR Spring Meeting", date: "March 2024" },
    { lat: 33.9221, lon: 18.4231, conference: "The Union North America Region", date: "February 2023" }
  ];
  
  var bounds = L.latLngBounds();
  talks.forEach(function(talk) {
    var marker = L.marker([talk.lat, talk.lon]).addTo(map)
                  .bindPopup(`<b>${talk.conference}</b><br>${talk.date}`);
    bounds.extend(marker.getLatLng());
  });
  map.fitBounds(bounds, { padding: [50, 50] });
</script>

