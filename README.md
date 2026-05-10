# RadarBot API 🚔

A lightweight Flask API that provides real-time speed camera and surveillance camera data displayed on an interactive map.

## ✨ Features

- 📡 REST API for radars and cameras
- 🗺️ Built-in interactive Leaflet map
- 🔄 Automatic data updates
- 🚨 Supports:
  - fixed speed cameras
  - turret radars
  - section control radars
  - red light cameras
  - mobile radars
  - unmarked radar cars
- 📷 Surveillance camera integration
- ⚡ Ready for Render / Gunicorn deployment
- 🔒 Built-in security headers
- ❤️ Healthcheck + monitoring endpoints

## 📂 Project Structure

- `main.py` → main Flask server :contentReference[oaicite:0]{index=0}
- `auto_update.py` → scraping & automatic data updater :contentReference[oaicite:1]{index=1}
- `camera.json` → cameras database :contentReference[oaicite:2]{index=2}
- `radars.json` → radars database :contentReference[oaicite:3]{index=3}
- `requirements.txt` → Python dependencies :contentReference[oaicite:4]{index=4}

## 🚀 Installation

```bash
git clone https://github.com/USERNAME/radarbot-api.git
cd radarbot-api

pip install -r requirements.txt
python main.py
