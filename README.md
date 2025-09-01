# 🌦️ Live Weather Dashboard Using API  

A dynamic **Power BI dashboard** that displays real-time weather data using [WeatherAPI.com](https://www.weatherapi.com) This dashboard allows users to visualize current and forecast weather metrics in an interactive, professional format.  

--- 

## 📑 Table of Contents
- 🔎 [Overview](#overview)    
- 🎯 [Why This Project](#why-this-project)  
- ✨ [Features](#features)  
- 🌐 [Data Source & API](#data-source--api)   
- ⚡ [Getting Started](#getting-started)    
  - 🛠️ [Prerequisites](#prerequisites)   
- 📊 [Usage](#usage)  
- 🎨 [Customization](#customization)
- 👤 [Author & Resources](#author--resources)   



---

## 🔎 Overview  

The **Live Weather Dashboard** is a Power BI solution that retrieves and displays weather data from an external API in real-time.  
It provides a comprehensive **visual summary of current conditions and forecasts**, helping users make informed decisions based on weather trends.  

---

## 🎯 Why This Project  

- 🌍 Offers easy access to **live weather data** in a rich, visual format.  
- ⚡ Demonstrates **integration of RESTful API data** into Power BI’s visualization engine.  
- 📈 Useful for applications such as **planning, analytics, or forecasting**.  
- 🎓 Serves as a **learning resource** for Power BI users to enhance dashboards with live data.  

---

## ✨ Features  

- 🌡️ **Current Weather Metrics** – Temperature, humidity, wind speed, pressure & more.  
- 📅 **Multi-Day Forecasts** – Daily/hourly weather forecast visualization.  
- 🔄 **Live Data Refresh** – Automated updates configured in Power BI.  
- 📊 **User-Friendly Visuals** – Intuitive charts, cards, and filters for quick insights.  

---

## 🌐 Data Source & API  

- 🔑 Uses **WeatherAPI.com** (or other weather APIs like Visual Crossing or OpenWeatherMap).  
- 📡 API Workflow:  
  1. 🔑 Get your **API key** from WeatherAPI.com.  
  2. 🌍 Construct API request URL (e.g., current weather/forecast).  
  3. 🔗 Connect via **Power BI → Get Data → Web**.  
  4. 🛠️ Transform JSON data with **Power Query**.  
  5. 📊 Build visuals (charts, cards, KPIs) in Power BI.  

📌 Example API URL:  
(https://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=New York&days=5&aqi=no&alerts=no)

---

### 🛠️ Prerequisites  
- 💻 Power BI Desktop (latest version).  
- 🔑 API Key from [WeatherAPI.com](https://www.weatherapi.com).  
- 📘 Basic knowledge of Power Query & Power BI visuals.

---

### 📊 Usage
- 🖥️ Explore dashboard pages with current & forecast visuals.
- 🖱️ Interact with filters, cards, and charts.
- 📅 Optional: Setup scheduled refresh in Power BI Service (Pro license). 

---

### 🎨 Customization
- 🌍 Add multiple cities with dynamic parameters.
- 📅 Extend forecast horizon (7-day ).
- 🖌️ Use custom visuals (KPIs, maps, gauges).
- ⚙️ Change units (Celsius/Fahrenheit) or language via API.

---

### 👤 Author & Resources
- 👨‍💻 Author: Om Sonawane
- 📖 Tutorial Reference: Youtube

---

### Screenshot

  - ![Alt text](https://github.com/OmSonawane-360/PowerBi-Dashboard-With-Weather-API/blob/main/WeatherAPI_Dashboard.png)


---
