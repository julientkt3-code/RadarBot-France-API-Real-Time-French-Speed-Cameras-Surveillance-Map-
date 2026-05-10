# RadarBot France API 🇫🇷🚔

A lightweight Flask API providing real-time French speed camera and surveillance camera data displayed on an interactive map.

Designed for France only.

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

- `main.py` → main Flask server :contentReference[oaicite:0]{index=0}
- `auto_update.py` → automatic scraping & updates :contentReference[oaicite:1]{index=1}
- `camera.json` → French surveillance cameras database :contentReference[oaicite:2]{index=2}
- `radars.json` → French speed cameras database :contentReference[oaicite:3]{index=3}
- `requirements.txt` → Python dependencies :contentReference[oaicite:4]{index=4}

## 🚀 Installation

```bash
git clone https://github.com/USERNAME/radarbot-france-api.git
cd radarbot-france-api

pip install -r requirements.txt
python main.py
