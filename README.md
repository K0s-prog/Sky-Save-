SkySave – Autonomous Search and Rescue Drone Swarm
Patent Filed (in progress hence confidential)

**Overview**
SkySave is an autonomous drone swarm system designed to assist in search and rescue operations in disaster-affected areas such as forests, islands, and other challenging terrains. The system uses multiple drones working collaboratively, equipped with cameras and machine learning models, to detect humans in real-time and provide rapid response capabilities.

**Key Features**
Autonomous Flight & Path Planning
Implements GPS-based recursive path planning for efficient area coverage.
Real-Time Human Detection
Uses ML-based object detection (YOLO) integrated with the drone's camera.
TCP Communication
Sends detected coordinates and images to a central server for quick action.
Adaptive Search Algorithm
Adjusts search pattern dynamically based on environmental conditions.
Swarm Coordination
Uses decentralized communication to avoid redundant scanning and optimize resource usage.

**Technology Stack**
**Hardware**: Pixhawk, Jetson Nano, GPS Module, Camera
**Software**: Python, OpenCV, YOLO v8, MAVLink
**Networking**: TCP/IP Protocol

**System Architecture**
**Drone Assembly** – Quadcopters with Pixhawk flight controller and Jetson Nano for onboard processing.
**Machine Learning **– YOLO v8 for real-time human detection on captured video feed.
**Communication** – Drones send data (image + GPS) to the central server via TCP sockets.
**Central Dashboard** – Displays detected locations and images for rescue teams.

**Use Case**
Disaster zones: Earthquakes, floods, forest areas
Military and security operations
Remote island rescue

**How It Works**
Drones take off and follow predefined GPS-based paths.
Cameras capture frames and run human detection inference.
On detection, coordinates + image are sent to the server.
Central system displays real-time alerts to rescue teams.
