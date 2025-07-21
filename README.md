# smart-traffic-system
# 🚦 Smart Traffic Management System

## Overview
A full-stack IoT-powered traffic control system built to optimize urban traffic flow using real-time sensor data and machine learning predictions. Designed to reduce congestion, improve safety, and support smarter city planning.

## Features
- 🧠 AI-powered adaptive signal timing
- 📡 Real-time sensor data handling (Raspberry Pi/Arduino simulation)
- 📊 Interactive dashboard with flow visualizations and route suggestions
- 📁 Scalable backend with MongoDB and PostgreSQL
- ⚙️ Admin controls for manual override and event-based modes

## Tech Stack
- **Frontend:** HTML5, Tailwind CSS, Chart.js
- **Backend:** FastAPI (Python), MongoDB, PostgreSQL
- **IoT Simulation:** Python scripts (mock sensors & traffic inputs)
- **ML Model:** Scikit-learn for prediction & route scheduling
- **Deployment:** Render/Vercel

## Real-World Use Cases
- Citywide traffic control centers
- Event logistics and crowd management
- Delivery route optimization for transport companies

## Setup Instructions
1. Clone the repo:  
   `git clone https://github.com/your-username/smart-traffic-system.git`
2. Navigate to project:  
   `cd smart-traffic-system`
3. Install backend dependencies:  
   `pip install -r requirements.txt`
4. Run mock IoT stream:  
   `python iot-simulation/traffic_sensor.py`
5. Launch dashboard from `/frontend` or host via Vercel/GitHub Pages



