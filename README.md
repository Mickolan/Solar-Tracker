# SolarTracker – Low‑Power Dual‑Axis Solar Tracking System

Development of an energy self-sufficient, robust solar tracking system.

SolarTracker is an ultra‑low‑power, autonomous dual‑axis solar tracking system designed as prototype with a small photovoltaic module (≈10 W). 
It uses an ESP32‑C3, NEMA17 stepper motors, LDR‑based sun sensing, and a 3S Li‑Ion battery pack charged via MPPT.
The system is engineered to operate efficiently, survive extended low‑sunlight periods, and optionally provide a local UI via a 16×2 LCD and 4‑key membrane keypad.
The intention is to develop the control system so that it can be used for significantly larger solar systems.

# Key Features
- Dual‑axis tracking using 4‑LDR sun sensor array
- Kalman‑filtered direction estimation for smooth, stable tracking
- Smart park mode (east‑facing, vertical) at sunset
- Ultra‑low‑power night mode with ESP32‑C3 deep sleep
- 3S Li‑Ion battery system with MPPT charging
- Battery monitoring, SOC estimation, and predicted runtime
- Optional local UI (LCD + keypad) for status, tuning, and diagnostics
- WLAN remote access for configuration and monitoring

# Project Structure
- Hardware architecture
- Energy management & dark‑doldrum survival strategy
- Tracking algorithm & Kalman filter
- Park logic with astronomical correction
- Optional UI system
- Bill of Materials (BOM)
- Hardware-Design will be another project

# Documentation
Extensive documentation, diagrams, algorithms, and design notes are available in the project Wiki.
