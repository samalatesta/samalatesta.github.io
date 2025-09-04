---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---


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
    { lat: 33.7490, lon: -84.3880, conference: "MIDAS Network Annual Meeting", date: "October 2023" },
    { lat: 39.29, lon: -76.61, conference: "ENAR Spring Meeting", date: "March 2024" },
    { lat: 49.15, lon: -123.06, conference: "The Union North America Region", date: "February 2023" }
  ];
  
  var bounds = L.latLngBounds();
  talks.forEach(function(talk) {
    var marker = L.marker([talk.lat, talk.lon]).addTo(map)
                  .bindPopup(`<b>${talk.conference}</b><br>${talk.date}`);
    bounds.extend(marker.getLatLng());
  });
  map.fitBounds(bounds, { padding: [50, 50] });
</script>

Here’s a curated list of invited talks and conference presentations I’ve given. 

---

## 2025 (Upcoming)

### **The Union World Conference on Lung Health**
- **Title:** *Smoked drug use drives tuberculosis transmission dynamics in a rural community in the Western Cape, South Africa*  
- **Date:** November 2025  
- **Location:** Copenhagen, Denmark
  
---

## 2024

### **ENAR 2024 Spring Meeting**
- **Title:** *Leveraging Active Case Finding Data to Identify Persons with TB Who Delay Seeking Care*  
- **Date:** March 2024  
- **Location:** Baltimore, Maryland

---

## 2023

### **The Union World Conference on Lung Health**
- **Title:** *TB disease burden among people who smoke illicit drugs: a respondent-driven sample, Western Cape, South Africa*  
- **Date:** November 2023  
- **Location:** Paris, France

- **Title:** *Benefits of diagnosing subclinical TB disease among people who smoke drugs*  
- **Date:** November 2023  
- **Location:** Paris, France 

- **Title:** *Alcohol’s effect on tuberculosis treatment response: a cohort study in the Western Cape, South Africa*  
- **Date:** November 2023  
- **Location:** Paris, France 

### **MIDAS Network Annual Meeting**
- **Title:** *Understanding tuberculosis care-seeking behavior from active case finding data*  
- **Date:** October 2023  
- **Location:** Atlanta, Georgia

### **New England Statistics Symposium**
- **Title:** *Inferring associations with respondent-driven sampling data*  
- **Date:** June 2023 
- **Location:** Boston, MA

---

## 2022

### **The Union World Conference on Lung Health**
- **Title:** *Alcohol exposure group classification using self-reported and biomarker measures in a South African cohort of persons with tuberculosis: a latent class analysis*  
- **Date:** November 2022 
- **Location:** Virtual

### **Molecular Biology and Human Genetics Divisional Seminar, Stellenbosch University**
- **Title:** *Methods for Handling Missing Data for Estimating Time to Mycobacterial Culture Conversion*  
- **Date:** July 2022 
- **Location:** Cape Town, South Africa




