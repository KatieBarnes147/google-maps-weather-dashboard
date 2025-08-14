# Google Maps Weather Dashboard (Keyless)

An interactive weather dashboard that shows current conditions for any point you click on the map.  
This version is **keyless**: it uses **Leaflet + OpenStreetMap** for maps and **Open-Meteo** for weather data (no API keys).

---

## 🚀 Live Demo
**GitHub Pages:** [View Live Project](https://katiebarnes147.github.io/google-maps-weather-dashboard/)

---

## ✨ Features
- Interactive map (Leaflet + OpenStreetMap) — no API key required
- Click anywhere to fetch current weather for that location
- Asynchronous JavaScript (`async/await`) for API calls
- Dynamic DOM updates on each map click
- Basic coordinate inputs (lat/lon) for manual lookups
- Responsive layout based on Week 3 project

---

## 🧰 Technologies Used
- HTML5  
- CSS3  
- Vanilla JavaScript  
- **Leaflet** (OpenStreetMap tiles)  
- **Open-Meteo** Weather API (no key)  
- GitHub Pages for hosting

---

## 🔐 Security Notes
- Weather data now uses **Open-Meteo** — **no API key required**.
- No weather API keys are stored in this repository or exposed in the client.
- (If you prefer Google Maps, use a **referrer-restricted** key and understand it will be visible client-side.)

---

## 🛠️ Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/KatieBarnes147/google-maps-weather-dashboard.git
   cd google-maps-weather-dashboard
   ```
2. Open `index.html` in your browser (or use a simple local server).
3. Click on the map to load weather for the selected location.

---

## 🧭 Notes
- If you need forecast or additional variables, extend the Open-Meteo URL with `daily=` or `hourly=` params.
- If you switch back to **Google Maps**, keep your API key **HTTP-referrer restricted** to your Pages domain.

