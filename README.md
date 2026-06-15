# 🌍 Real-Time Global Weather Analysis Dashboard

> Live worldwide weather data, comparative analysis, and forecasts powered by OpenWeatherMap REST API — built with Python, Django, and vanilla JS.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Django](https://img.shields.io/badge/Django-4.2-green)
![API](https://img.shields.io/badge/OpenWeatherMap-REST%20API-orange)
![Status](https://img.shields.io/badge/Status-Complete-green)

---

## 📌 Overview

A full-stack weather intelligence dashboard that fetches real-time weather data for cities worldwide and presents it through an interactive, responsive web interface. Features live search, global city comparisons, temperature/humidity analysis charts, and sunrise/sunset tracking.

---

## ✨ Features

- 🔍 **Live City Search** — Search any city worldwide with real-time data
- 🌐 **Global Cities Panel** — Auto-loads weather for 8 major world cities
- 📊 **Comparative Charts** — Temperature and humidity bar charts across cities
- 🌡️ **Detailed Metrics** — Temp, feels-like, humidity, wind speed, pressure, visibility, sunrise/sunset
- 🎨 **Temperature Colour Coding** — Visual heat-map style colour by temperature range
- 📱 **Responsive Design** — Works on mobile, tablet, and desktop

---

## 🚀 How to Run

### 1. Get API Key (Free)
```
1. Go to https://openweathermap.org/api
2. Sign up for free
3. Copy your API key
```

### 2. Setup & Run
```bash
git clone https://github.com/Harver23/weather-global-analysis.git
cd weather-global-analysis
pip install -r requirements.txt

# Add your API key to templates/index.html
# Replace: const API_KEY = 'YOUR_OPENWEATHERMAP_API_KEY';

python manage.py runserver
# Open http://127.0.0.1:8000
```

---

## 📁 Project Structure

```
weather-global-analysis/
├── templates/
│   └── index.html          # Full frontend — search, live data, charts
├── static/
│   ├── css/
│   └── js/
├── images/
├── views.py                # Django backend views
├── requirements.txt
└── README.md
```

---

## 🛠️ Tech Stack

`Python` `Django` `OpenWeatherMap REST API` `HTML5` `CSS3` `JavaScript (Fetch API)`

---

## 📊 Data Points Per City

| Metric | Description |
|---|---|
| Temperature | Current + feels-like (°C) |
| Humidity | % relative humidity |
| Wind Speed | m/s |
| Pressure | hPa (millibars) |
| Visibility | km |
| Sunrise/Sunset | Local time |
| Weather Description | Clear, Cloudy, Rain, etc. |

---

## 👤 Author

**Harender Deep Singh**
B.E. AI & ML — Sambhram Institute of Technology, Bengaluru
[LinkedIn](https://www.linkedin.com/in/harender-deep-singh-814784338) | [GitHub](https://github.com/Harver23)
