Overview

This project simulates a drone traveling across major Indian cities to monitor air quality. It generates pollution readings from both fixed stations and a mobile drone sensor, processes the data, computes India’s official CPCB National AQI (NAQI), detects anomalies, and visualizes results on an interactive heatmap.

✨ Features

Multi-city drone route simulation

Dual data sources (Station + Mobile)

Pollution hotspot influence modeling

CPCB NAQI AQI calculation

Rolling mean smoothing

Z-score anomaly detection

CSV dataset export

Interactive HTML heatmap

📊 Pollutants Included

PM2.5

PM10

CO

NO₂

SO₂

AQI is calculated using the Maximum Sub-Index method as per CPCB guidelines.

🛠 Tech Stack

Python

Pandas

NumPy

Folium (Geospatial Visualization)

drone_aqi_data_full.csv – Processed dataset

drone_aqi_map_full.html – Interactive AQI heatmap

📈 Data Pipeline

Simulate pollutant readings

Clamp unrealistic values

Apply rolling smoothing

Detect anomalies (Z-score > 3)

Compute AQI (CPCB breakpoints)

Generate visualization

🎯 Learning Outcomes

Environmental data simulation

AQI algorithm implementation

Data preprocessing techniques

Geospatial data visualization
