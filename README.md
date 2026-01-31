# Tell My Location 📍

**The fastest "Where am I?" tool on the internet.**

[Visit Website](https://tellmylocation.com)

## 🚀 About
TellMyLocation is a lightweight, high-precision web utility designed to instantly provide users with their exact GPS coordinates, physical address, and local weather data. It features a **One-Tap SOS** system for emergencies and operates entirely client-side for maximum privacy.

## ✨ Key Features
* **Instant GPS Lock:** Displays Latitude, Longitude, and Accuracy (± meters).
* **Smart Address Lookup:** Converts raw coordinates into a readable street address.
* **🚨 One-Tap SOS:** Generates an emergency SMS or WhatsApp link containing live location data.
* **Nearest Services:** Automatically locates the closest Police Station, Hospital, and Gas Station.
* **Dual Units:** Auto-calculates Metric (°C / km) and Imperial (°F / mi) simultaneously.
* **Global Language Engine:** Supports English, Spanish, French, Russian, and Arabic (with RTL layout).
* **Dark Mode UI:** Optimized for low-light environments and battery saving.

## 🛠️ Technologies Used
* **Frontend:** HTML5, CSS3 (Glassmorphism), Vanilla JavaScript.
* **Mapping:** Leaflet.js & OpenStreetMap.
* **Data APIs:** Open-Meteo (Weather), Nominatim (Reverse Geocoding), Overpass API (Emergency Services).
* **Performance:** Zero-dependency architecture (Loads in <1 second).

## 🔒 Privacy & Security
This application is built with a **Privacy-First** architecture.
* **Client-Side Processing:** Location data is accessed via the browser's Geolocation API and displayed locally.
* **No Database:** We do not store, log, or track user movements.
* **Secure:** Runs entirely over HTTPS.

## 📦 Installation / Deployment
This project is a static web application. It requires no backend server configuration.
1.  Upload `index.html`, `privacy.html`, and `ads.txt` to your host (GitHub Pages, Netlify, or Apache/Nginx).
2.  Ensure your domain has an SSL certificate (HTTPS) enabled, as modern browsers require secure contexts for Geolocation features.

---
&copy; 2025 TellMyLocation.com
