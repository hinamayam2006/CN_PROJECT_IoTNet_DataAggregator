# IoT Smart Campus Dashboard 🎓

**Project:** CN_PROJECT_IoTNet_DataAggregator
**Stack:** Node-RED, JavaScript, CSS (Glassmorphism UI)

## Overview
This project is a real-time **IoT Data Aggregator and Dashboard** designed for a Smart Campus environment. It simulates and visualizes sensor data from multiple rooms (Classrooms and Labs), monitoring metrics like **Temperature, Humidity, CO2, Noise, Light, and Occupancy.**

## Key Features
* **Sci-Fi/Cyberpunk UI:** Custom CSS ("Cyber-Slate" theme) with neon glowing effects.
* **Live Data Simulation:** Generates realistic dummy data for 8 different zones.
* **Smart Filtering:** Dropdown selection to switch views between specific rooms (CR-24, Lab-10, etc.).
* **Dynamic Visuals:**
    * **Neon Gauges** for Temp & Humidity.
    * **Active/Idle Badges** with pulsing animations.
    * **Trend Charts** for historical analysis.
* **Custom Tables:** A transparent, auto-scrolling HTML table for data logging.

## How to Run
1.  Install [Node-RED](https://nodered.org/).
2.  Install the Dashboard dependency: `npm install node-red-dashboard`.
3.  Import `flows.json` into your Node-RED instance.
4.  Deploy and visit `/ui`.