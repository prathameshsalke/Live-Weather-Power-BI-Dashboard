# 🌦️ Live Weather, AQI & Forecast Dashboard

A real-time, interactive Power BI dashboard built to track and visualize current weather conditions, air quality index (AQI), and 5-day weather forecasts for cities around the globe using live API data.

---

## 📝 Short Description / Purpose

The **Live Weather, AQI & Forecast Dashboard** is designed to help individuals, city planners, health officials, and businesses monitor environmental conditions in real time. It provides live insights into temperature, humidity, air pollution levels, and weather forecasts to support safety, logistics, and strategic decisions.

---

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:<br>

• 📊 **Power BI Desktop** – Primary platform for data visualization and report building  
• 🔗 **Web API (OpenWeatherMap)** – Source for live weather and air quality data  
• 🧹 **Power Query (M language)** – Used to transform JSON data fetched from APIs  
• 🧠 **DAX (Data Analysis Expressions)** – For calculated fields and conditional visuals  
• 🌐 **Power BI Service** – For publishing dashboards and scheduling refresh  
• 📝 File Format – `.pbix` for dashboard, `.png` for previews

---

## 📂 Data Source

• **Weather & AQI Data**: [OpenWeatherMap API](https://openweathermap.org/api)  
  - `/data/2.5/weather`: Current temperature, wind speed, humidity, etc.  
  - `/data/2.5/air_pollution`: Air quality index, PM2.5, PM10, CO, NO₂, SO₂, O₃  
  - `/data/2.5/forecast`: 5-day forecast in 3-hour intervals  

Data is updated live with scheduled refreshes in Power BI Service.

---

## 🔍 Features / Highlights

### • Business Problem

Cities, travelers, and businesses need **up-to-date information on weather and air quality** to protect public health, optimize operations, and plan activities. Without a unified dashboard, users have to check multiple sources, making decision-making slow and fragmented.

---

### • Goal of the Dashboard

To deliver a **real-time environmental intelligence dashboard** that:

- 🌍 Tracks weather and AQI conditions by city  
- 📈 Shows trends using time series charts  
- 🔍 Allows users to filter data by location or condition  
- 📊 Supports planning and response across sectors  

---

### • Walkthrough of Key Visuals

- **Weather KPIs (Top Row)**  
  - Current Temperature, Humidity, Wind Speed  
  - Feels Like Temperature, Visibility, UV Index  

- **AQI Overview (Cards + Chart)**  
  - AQI Value, Health Risk Indicator (Good, Moderate, Unhealthy)  
  - Bar chart for PM2.5, PM10, NO₂, CO  

- **Forecast Line Chart**  
  - 5-day hourly temperature trend  
  - Rain Probability or Humidity levels  

- **Geo Map Visualization**  
  - Visual AQI heatmap by cities  
  - Tooltip with real-time stats  

---

### • Business Impact & Insights

| Use Case        | Insights / Benefits                                 |
|------------------|------------------------------------------------------|
| **Tourism**       | Identify best times for travel and outdoor events   |
| **Healthcare**    | Alert asthma patients during poor air quality       |
| **Smart Cities**  | Support emergency response and pollution tracking   |
| **Logistics**     | Avoid weather delays in fleet movement              |
| **Public Safety** | Inform citizens about heatwaves or pollution spikes |

---

## ❓ Key Questions Answered

- What’s the current air quality in my city?
- Will the weather be suitable for travel in the next 5 days?
- How does air quality vary by region and time?
- Are pollution levels increasing or decreasing this week?

---

## 📸 Screenshots / Demos

### Dashboard Report 
![AQI Cards](https://github.com/prathameshsalke/Live-Weather-Power-BI-Dashboard/blob/main/Live%20weather%20Report.png)

### Dashboard Video 
![Dashboard Preview](https://github.com/prathameshsalke/Live-Weather-Power-BI-Dashboard/blob/main/Live%20Weather%20Report%20video.mp4)





---

## 📁 Project Files

- `Weather_AQI_Dashboard.pbix` – Main Power BI file  
- `screenshots/` – Dashboard images  
- `README.md` – This file


---

## 📬 Contact

For any questions or collaboration ideas, reach out at:  
📧 prathameshsalke8094@gmail.com
🌐 [LinkedIn](www.linkedin.com/in/prathamesh-salke-57a169281)

