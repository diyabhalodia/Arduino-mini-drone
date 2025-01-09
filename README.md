# Arduino-mini-drone
# Overview
A low-cost, customizable quadcopter drone built using Arduino and open-source components, designed for hobbyists and researchers to explore drone technology and autonomous flight.

# Features
1) Flight Control: Utilizes an Arduino-based PID control system for stable flight.
2) Sensor Integration: Includes MPU-6050 for gyroscope readings to maintain balance and stability.
3) Battery Monitoring: Real-time voltage and current tracking to ensure safe operation.
4) Customizable: Easily modifiable hardware and software for personalized configurations.

# Components
1) Arduino (Pro Mini/Uno)
2) MPU-6050 (Gyroscope and Accelerometer)
3) Receiver Module (PulsePosition library)
4) Motors and ESCs (Electronic Speed Controllers)
5) LiPo Battery

# How It Works
-> Processes inputs from a remote controller for throttle, pitch, roll, and yaw using PulsePosition.
-> Reads gyroscopic data to calculate angular rates and errors.
-> Applies a PID control loop to stabilize flight by adjusting motor speeds.
-> Monitors battery levels for safe operation with low-battery warnings.

# Setup
1) Connect all components as per the circuit diagram.
2) Upload the provided code using Arduino IDE.
3) Calibrate the gyroscope during the initial setup.
4) Power the drone and take off!

# Applications
Autonomous drone experiments.
DIY drone building and customization.
Research and learning projects in robotics and embedded systems.
