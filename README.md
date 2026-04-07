# Autonomous Underwater Vehicle (AUV)

Developed this project as part of the **Robofest Gujarat 5.0 (GUJCOST) AUV Challenge**, focusing on designing and building a fully functional Autonomous Underwater Vehicle for real-world underwater tasks.

The system integrates mechanical design, embedded systems, and computer vision to perform operations such as navigation, inspection, and object interaction.

---

## 🚀 Overview

The AUV features:

* PVC frame for structural strength and low drag
* Six-thruster configuration enabling multi-axis control
* Raspberry Pi for high-level processing and Pixhawk (ArduSub) for stabilization
* Vision pipeline using OpenCV for perception tasks

The vehicle is capable of controlled motion in surge, sway, heave, and yaw, ensuring stable underwater navigation.

---

## ⚙️ System Design

### Mechanical System

* Rigid and modular frame design with balanced mass distribution
* 6 thruster configuration for dof 
* Waterproof electronics enclosure
* Dedicated mounts for sensors, camera, and manipulator

### Electronics & Control

* Pixhawk 2.4.8 for real time control and sensor fusion
* Raspberry Pi 4 running BlueOS and ROS2
* ESC-controlled BLDC motors for propulsion
* Sensors: camera, pressure sensor, leak detection

### Software

* ROS2 + MAVROS architecture
* MAVLink communication
* OpenCV-based perception
* QGroundControl for monitoring and mission execution

---

## Contributions

* Designed key mechanical components and assemblies using **Fusion 360**
* Worked on structural layout, stability, and component integration
* Developed mounts and enclosure systems for underwater operation
* Contributed to vision pipeline with **HSV-based color segmentation using OpenCV**

---

## 🏆 Achievements

* Advanced to **Round 2** in Robofest Gujarat 5.0
* Secured **₹50,000 in project funding**
* Successfully developed and presented a working prototype

---

## 📂 Repository Structure

* `mechanical-design/` → CAD models and components
* `system-design/` → full AUV assemblies and iterations
* `gripper/` → manipulator design

---

## 🛠️ Tools & Technologies

Fusion 360 • ROS2 • OpenCV • MAVLink • Raspberry Pi • Pixhawk • 3D Printing

---

## 📸 Preview

<img width="1920" height="782" alt="AUVbody_ideation" src="https://github.com/user-attachments/assets/faaa05d7-76f6-457e-8759-ab5112cec109" />


---
