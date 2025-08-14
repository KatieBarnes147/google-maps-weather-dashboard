# Google Maps Weather Dashboard

An interactive weather dashboard that combines the **Google Maps JavaScript API** with **Open-Meteo** (keyless) for current weather.  
Click anywhere on the map to retrieve live conditions for that location. This project demonstrates **maps integration, async JavaScript, and DOM updates**.

---

## 🚀 Live Demo
**GitHub Pages:** [View Live Project](https://katiebarnes147.github.io/google-maps-weather-dashboard/)

---

## ✨ Features
- Google Maps JavaScript API for an interactive map
- Click-to-query weather by latitude/longitude
- Weather data from **Open-Meteo** (no API key required)
- Asynchronous JavaScript (`async/await`)
- Dynamic DOM updates on each map click
- Simple coordinate inputs for manual lookups
- Responsive layout (based on Week 3 project)

---

## 🧰 Technologies Used
- HTML5  
- CSS3  
- Vanilla JavaScript  
- **Google Maps JavaScript API**  
- **Open-Meteo** Weather API (keyless)  
- GitHub Pages for hosting

---

## 🔐 Security Notes
- Weather data uses **Open-Meteo** — **no weather API key** is stored in this repo.
- The **Google Maps API key** is present in the client (as required by Google Maps JS) and is **strictly restricted by HTTP referrer** to this site’s domain.
- For fully secret server-side keys (not needed here), use a small proxy or serverless function.

---

## 🛠️ Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/KatieBarnes147/google-maps-weather-dashboard.git
   cd google-maps-weather-dashboard
   ```
2. Open `index.html` in your browser (or serve locally).
3. Click on the map to load weather for the selected location.

---

## 🧭 Notes
- To add forecasts or more variables, extend the Open-Meteo URL with `daily=` or `hourly=` parameters.
- Keep your Google Maps key **HTTP-referrer restricted** to:
  ```
  https://katiebarnes147.github.io/*
  ```

