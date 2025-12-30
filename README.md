# CanSat Team Project

Welcome to the official repository of the **AltitudeX** CanSat project! This repository contains all resources, code, and documentation for our CanSat mission.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Mission Objectives](#mission-objectives)  
- [System Architecture](#system-architecture)  
- [Hardware](#hardware)  
- [Software](#software)  
- [Installation](#installation)  
- [Usage](#usage)  
- [License](#license)  

---

## Project Overview

Our CanSat project aims to design, build, and launch a miniature satellite that can collect environmental data and perform scientific experiments.  
This project is part of CanSat UK and serves as a platform for learning and applying aerospace engineering concepts.

---

## Mission Objectives

1. **Primary Mission:** Collect data on the temperature and pressure of the atmosphere around the CanSat, and transmit it to a ground station every second at the minimum.  
2. **Secondary Mission:** Measure the humidity of the atmosphere around the CanSat, and use that to make graphs and improve understanding of the atmophere.
3. **Data Transmission:** We will send the data recorded on the CanSat to the ground station in real time.

---

## System Architecture

The CanSat system is divided into the following subsystems:

- **Flight Module:** Handles flight stabilization, sensor data acquisition, and communication.  
- **Ground Station:** Receives telemetry, logs data, and monitors mission progress.  
- **Payload Module:** Conducts scientific experiments and captures experimental data.

---

## Hardware

Key hardware components:

- Microcontroller: Raspberry Pi pico
- Sensors: BME688  
- Communication: RFM96W LoRa 433MHz Transceiver breakout  
- Power Supply: LiPo battery
- Structural Components: 3D-printed frame, parachute system

---

## Software

The CanSat software stack includes:

- **Firmware:** Runs on the microcontroller for sensor reading, data logging, and telemetry.  
- **Ground Station:** Python scripts for receiving, logging, and visualizing telemetry.  
- **Data Analysis:** Scripts for analyzing and plotting mission data.
