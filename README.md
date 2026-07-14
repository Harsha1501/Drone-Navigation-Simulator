# 🚁 Drone Navigation & Waypoint Planner

A Python-based drone navigation simulator that demonstrates autonomous waypoint planning, obstacle avoidance, mission visualization, animated drone flight, and JSON mission reporting.

---

## 📌 Project Overview

This project simulates an autonomous drone navigating through multiple waypoints while avoiding no-fly zones in a 2D environment.

The simulator demonstrates fundamental robotics and UAV navigation concepts including path planning, waypoint navigation, mission execution, and visualization.

---

## 🚀 Features

- 2D Drone Navigation Simulation
- Multiple Waypoint Navigation
- No-Fly Zone Representation
- Flight Path Visualization
- Animated Drone Movement
- Waypoint Labeling
- Professional Map Legend
- Mission Statistics
- JSON Mission Report Export

---

## 🛠 Technologies Used

- Python 3
- NumPy
- Matplotlib
- JSON
- Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```text
drone-navigation-simulator/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── notebook/
│   └── Drone_Navigation.ipynb
│
├── outputs/
│   ├── flight_path.png
│   ├── drone_mission.json
│   └── mission_summary.txt
│
└── screenshots/
    ├── 01_environment.png
    ├── 02_flight_path.png
    ├── 03_animation.png
    ├── 04_waypoints.png
    ├── 05_professional_map.png
    ├── 06_console_report.png

```

---

## ⚙ Workflow

```text
Initialize Environment
          │
          ▼
Place Drone
          │
          ▼
Add Waypoints
          │
          ▼
Create No-Fly Zones
          │
          ▼
Plan Flight Route
          │
          ▼
Animate Drone Flight
          │
          ▼
Visit Waypoints
          │
          ▼
Generate Mission Statistics
          │
          ▼
Export JSON Report
```

---


## 📊 Sample Console Output

```text
=============================================
DRONE MISSION REPORT
=============================================

Mission Status     : SUCCESS
Waypoints Visited  : 4
Flight Distance    : 10 Units
No-Fly Zones       : 12
Drone ID           : Drone-01

=============================================
```

---

## 📄 Sample JSON Output

```json
{
    "drone": "Drone-01",
    "waypoints": 4,
    "distance": 10,
    "obstacles": 12,
    "status": "Mission Complete"
}
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/Harsha1501/drone-navigation-simulator.git
```

Navigate to the project folder:

```bash
cd drone-navigation-simulator
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebook/Drone_Navigation.ipynb
```

Run all cells to execute the simulation.

---

## 🎯 Learning Outcomes

This project demonstrates:

- Drone Navigation
- Waypoint Planning
- Path Visualization
- Obstacle Representation
- Mission Planning
- UAV Simulation
- Robotics Programming
- Data Visualization
- JSON Report Generation

---

## 🚀 Future Improvements

- A* Path Planning
- Dynamic Obstacles
- GPS Coordinate Simulation
- Battery Monitoring
- Wind Effect Simulation
- Altitude Control
- Multi-Drone Coordination
- ROS 2 Integration
- Gazebo Simulation
- Real-Time Drone Telemetry

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Harsha**

GitHub: https://github.com/Harsha1501