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
  // Initialize map (initial center/zoom will be overridden by fitBounds)
  var map = L.map('talks-map');

  // Add a clean, subtle tile layer (Carto Light)
  L.tileLayer('https://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}{r}.png', {
      attribution: '&copy; OpenStreetMap &copy; CARTO',
      subdomains: 'abcd',
      maxZoom: 19
  }).addTo(map);

  // List of talks with coordinates, conference title, and date
  var talks = [
    { lat: 42.3601, lon: -71.0589, conference: "International Conference on Infectious Disease Modeling", date: "March 15, 2025" },
    { lat: 38.9072, lon: -77.0369, conference: "APHA Annual Meeting", date: "November 5, 2024" },
    { lat: 51.5074, lon: -0.1278, conference: "International Biostatistics Workshop", date: "September 8, 2023" },
    { lat: 41.8781, lon: -87.6298, conference: "SER Conference", date: "June 12, 2024" }
  ];

  // Create a LatLngBounds object to track all markers
  var bounds = L.latLngBounds();

  // Add markers and popups
  talks.forEach(function(talk) {
    var marker = L.marker([talk.lat, talk.lon]).addTo(map)
                  .bindPopup(`<b>${talk
