# MonVoy
My Personal Travel Log

# ✈️ MonVoy - Personal Travel Log

<div align="center">
  <img src="https://github.com/Hummels0211/MonVoy/blob/main/Images/MonVoy_logo.png.png" alt="MonVoy Logo" width="400"/>
  <br>
  <br>

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Made with](https://img.shields.io/badge/Made%20with-HTML%20%26%20JS-orange)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  [![Style](https://img.shields.io/badge/Style-Tailwind-blue)](https://tailwindcss.com/)
</div>

<br>

**MonVoy** is a modern, privacy-focused travel journal application that runs entirely in your browser. It allows you to log your trips, visualize your flight paths on an interactive map, edit travel photos, and generate beautiful, shareable "Year in Review" reports.

## ✨ Features

* **🗺️ Interactive World Map:** Visualize your journeys with flight paths connected to your home base.
* **📍 Smart Location Search:** Auto-detects country codes and coordinates for cities worldwide.
* **🎨 Dynamic Themes:** Switch between Modern, Clean (Positron), Classic (OSM), and Dark Mode.
* **📸 Built-in Photo Studio:** Upload, crop, and apply filters (Vivid, Vintage, B&W) to your travel memories directly in the app.
* **🏳️ Passport Stamp Collection:** Automatically collects high-quality flag icons for every country you visit.
* **📊 Annual Report (Wrapped):** Generates a Spotify-style "Journey Wrapped" card with statistics, travel personas, and photo reels.
* **📱 Social Sharing:** Export your report as a high-quality image for Instagram, WhatsApp, or Twitter.
* **🔒 Privacy First:** All data is stored locally in your browser (`localStorage`). No external servers, no tracking.
* **💾 Import/Export:** Backup your travel history to a JSON file and restore it on any device.

## 🛠️ Tech Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN)
* **Mapping:** [Leaflet.js](https://leafletjs.com/) & [Natural Earth Vectors](https://www.naturalearthdata.com/)
* **Map Tiles:** CartoDB & OpenStreetMap
* **Imaging:** [html2canvas](https://html2canvas.hertzen.com/) (for generating screenshots)
* **Icons:** [FontAwesome](https://fontawesome.com/) & [FlagCDN](https://flagcdn.com/)

## 🚀 Getting Started

Since MonVoy is a static web application, you don't need a backend server or complex installation process.

### Option 1: Quick Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/Hummels0211/MonVoy.git](https://github.com/Hummels0211/MonVoy.git)
    ```
2.  Simply open `index.html` in any modern web browser (Chrome, Firefox, Safari).

### Option 2: Local Server (Recommended)
For the best experience (to avoid CORS issues with some browser security settings), run it on a local server.

If you have Python installed:
```bash
python -m http.server 8000
# Then visit http://localhost:8000
