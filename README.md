# RadarBot France API 🇫🇷🚔

A lightweight Flask API providing real-time French speed camera and surveillance camera data displayed on an interactive map.

Designed for France only.

🌐 Live Demo: https://radarbot-sey0x.onrender.com/

## ✨ Features

- 📡 REST API for French radars and cameras
- 🗺️ Interactive Leaflet map
- 🔄 Automatic hourly data updates
- 🚨 Supports:
  - fixed speed cameras
  - turret radars
  - section control radars
  - red light cameras
  - mobile radars
  - unmarked radar cars
- 📷 Surveillance camera integration
- ⚡ Render / Gunicorn deployment ready
- 🔒 Built-in security hardening
- ❤️ Healthcheck + monitoring endpoints
- 🇫🇷 French nationwide radar database

## 📂 Project Structure

- `main.py` → main Flask server
- `auto_update.py` → automatic scraping & updates
- `camera.json` → French surveillance cameras database
- `radars.json` → French speed cameras database
- `requirements.txt` → Python dependencies

## 🚀 Installation

```bash
git clone https://github.com/USERNAME/radarbot-france-api.git
cd radarbot-france-api

pip install -r requirements.txt
python main.py
```

## 🌐 API Endpoints

### Get all radars
```http
GET /api/radars
```

### Get all cameras
```http
GET /api/cameras
```

### Server status
```http
GET /api/status
```

### Healthcheck
```http
GET /health
```

### Force update
```http
POST /api/force-update
```

## 🛠️ Tech Stack

- Python
- Flask
- APScheduler
- Gunicorn
- Leaflet.js
- OpenStreetMap
- Render

## 📱 Responsive Design

Optimized for:
- Desktop
- Mobile
- Tablets

## ⚠️ Disclaimer

This project is made for educational and experimental purposes only.

All radar and camera data comes from public or community-based sources available in France.

## 📜 License

MIT License
