# 🌐 SkySave – Autonomous Search and Rescue Drone Swarm  
**Patent Filed**(in progress hence confidential)

---

## Overview  
SkySave is an **autonomous drone swarm system** designed for **search and rescue operations** in disaster-hit regions such as forests, islands, and difficult terrains.  
Each drone is equipped with a **camera and a machine learning-based detection model** to identify humans in real time.  
The system uses **GPS-based path planning**, **TCP communication**, and a **decentralized coordination protocol** to optimize search coverage.

---

## Key Features
- **Autonomous Flight & Path Planning**  
  - Implements **GPS-based recursive path planning** for efficient coverage.  
- **Real-Time Human Detection**  
  - Uses **YOLO (Machine Learning)** integrated with drone cameras.  
- **TCP Communication**  
  - Transfers **detected coordinates and images** to the central server instantly.  
- **Adaptive Search Algorithm**  
  - Dynamically adjusts search based on environmental conditions.  
- **Swarm Collaboration**  
  - Decentralized communication prevents redundant scanning.

---

## Tech Stack
- **Hardware:** Pixhawk, Jetson Nano, GPS Module, Camera  
- **Software:** Python, OpenCV, YOLO, MAVLink  
- **Networking:** TCP/IP Protocol  

---

## System Architecture
1. **Drone Assembly:** Quadcopters using Pixhawk & Jetson Nano for onboard processing.  
2. **Machine Learning:** YOLO model for real-time human detection on video feed.  
3. **Communication:** TCP sockets for sending detection data (image + GPS) to server.  
4. **Central Dashboard:** Displays live alerts for rescue teams.  

---

## Use Cases
- Disaster zones: Earthquakes, floods, forest areas  
- Military & security search missions  
- Remote island rescue operations  

---

## How It Works
1. Drones take off and follow **predefined GPS-based paths**.  
2. Cameras capture frames → **ML detects humans in real time**.  
3. On detection → **Coordinates + Image sent to central server**.  
4. **Rescue teams get live alerts and exact locations**.  

---
## Images
![drone(skysave)](https://github.com/user-attachments/assets/3187b338-3a14-44bc-94ca-fdd212eeb4f9)
![drone(ml)](https://github.com/user-attachments/assets/13258998-3c3e-4c17-9e82-154e7e45379a)



