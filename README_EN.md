# AI Navigation Assistance System  
Autonomous Campus Guide Vehicle (SLAM × YOLOv4 × Voice Control × Embedded Integration)

This project presents an autonomous navigation vehicle designed for campus guidance.  
The system integrates LiDAR SLAM, YOLOv4 building recognition, voice command input, and cross-platform embedded control to provide intelligent, real-time navigation without human intervention.

🎥 Demo Video: https://www.youtube.com/watch?v=_xXVmry_xc8  
🏆 Smart Innovation Competition 2024 — *Honorable Mention*

---

## 📌 Overview
The vehicle autonomously performs localization, map construction, path planning, and obstacle avoidance in real campus environments. Users can specify destinations through voice commands, and the system plans and follows an optimal route automatically.

---

## 🧭 System Architecture
- **LiDAR & SLAM**: RPLIDAR A1 with ROS hector_mapping  
- **Navigation**: D\* Lite global planning, DWA local obstacle avoidance  
- **Vision**: YOLOv4 building detection (custom dataset, 4500+ images)  
- **Voice Input**: Speech-based destination selection  
- **Integration**: Raspberry Pi, Arduino, MATLAB GUI, 5G/Wi-Fi communication  

---

## 🔧 Technical Highlights
- Real-time LiDAR-based SLAM  
- Custom YOLOv4 training pipeline  
- D\* Lite path planning and DWA obstacle avoidance  
- MATLAB GUI visualization  
- Embedded motor control on Raspberry Pi + Arduino  

---

## 🌟 Results
- Stable autonomous navigation in campus environments  
- Reliable building recognition  
- Real-time visualization of map, path, detections, and video feed  
- Voice-controlled destination input  
