# 🏎️ QTR-8RC based High-Speed Line Follower
<img width="900" height="900" alt="axon_lfr" src="https://github.com/user-attachments/assets/dd5d941a-a56a-45b1-8a7a-13d677d7174a" />


An autonomous, high-speed line following robot built around the Pololu QTR-8RC reflectance sensor array. This project utilizes precise PID control written in **Python**, running via an Arduino Mega, to achieve smooth and rapid navigation through complex tracks, sharp corners, and crossovers.

## ✨ Features

* **High-Speed & Precision:** Powered by 900 RPM N20 motors with built-in encoders, allowing for accurate speed regulation and odometry feedback.
* **Aggressive Power Delivery:** Runs on a 1000mAh 3S LiPo battery for rapid acceleration and sustained top speed through straightaways.
* **Direct-Mount Architecture:** Components are routed and mounted directly to the Arduino Mega for a straightforward, accessible hardware stack without the need for a custom PCB.
* **High-Resolution Sensing:** Utilizes the 8-channel QTR-8RC array for fast, precise line position calculation.
* **On-the-Fly PID Tuning:** Integrated 0.96" OLED display interface allows for real-time adjustments of Proportional, Integral, and Derivative constants.

## 🛠️ Hardware Components

* **Microcontroller:** Arduino Mega 2560 (Non-WiFi)
* **Sensor Array:** Pololu QTR-8RC Reflectance Sensor Array
* **Motors:** N20 DC Gear Motors (900 RPM) with Encoders
* **Motor Driver:** L298N Dual H-Bridge Motor Driver
* **Display:** 0.96" I2C OLED Display (for UI/tuning)
* **Power:** 1000mAh 3S LiPo Battery 

## 💻 Software & Tools

* **Language:** Python
* **Control Algorithm:** Custom PID loop integrating sensor data and encoder feedback for flawless trajectory tracking.

1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/Your-Repo-Name.git](https://github.com/YourUsername/Your-Repo-Name.git)
