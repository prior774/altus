# Altus — Real‑Time Disaster & Weather Information Discord Bot

Altus is a lightweight and reliable Discord bot that provides real‑time disaster and weather information using trusted sources such as:

- Japan Meteorological Agency (JMA)
- United States Geological Survey (USGS)
- National Oceanic and Atmospheric Administration (NOAA)
- Open‑Meteo Weather API

Altus delivers essential data including earthquakes, tsunamis, typhoons, hurricanes, cyclones, weather alerts, and global weather reports.

---

## 🚀 Key Features

- Earthquakes — Japan (JMA) / Global (USGS)
- Tsunamis — Japan (JMA) / Global (USGS)
- Typhoons — JMA
- Hurricanes — NOAA
- Cyclones — NOAA
- Weather Alerts — JMA
- Weather Reports — Japan (JMA) / Global (Open‑Meteo)

---

## 📚 Commands

| Command          | Description                               |
|------------------|-------------------------------------------|
| `!earthquake`    | Latest Japan + global earthquake data      |
| `!tsunami`       | Latest tsunami information                 |
| `!typhoon`       | Typhoon updates                            |
| `!hurricane`     | Hurricane updates                          |
| `!cyclone`       | Cyclone updates                            |
| `!alert`         | Weather alerts                             |
| `!weather Tokyo` | Weather (auto Japan/Global detection)      |

---

## 📦 Installation

### Required Libraries

discord.py  
aiohttp  

---

## 📁 Directory Structure

altus-disaster-weather-bot/  
│ main.py  
│ bot.py  
│ config.json  
│ README.md  
│ README_EN.md  
│ requirements.txt  
└─cogs/  
　│ earthquake.py  
　│ tsunami.py  
　│ typhoon.py  
　│ hurricane.py  
　│ cyclone.py  
　│ alert.py  
　│ weather.py  

---

## ⚙ Configuration (config.json)

```json
{
  "token": "YOUR_BOT_TOKEN",

  "colors": {
    "weather": "0x00aaff",
    "earthquake": "0xff4444",
    "typhoon": "0x1e90ff",
    "cyclone": "0x00ccff",
    "hurricane": "0xff6600",
    "tsunami": "0x0066ff",
    "alert": "0xff3333"
  }
}

---

## 📄 License

This project is licensed under the MIT License.  
See the LICENSE file for full details.
