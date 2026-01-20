# PPG Sensor & Processing Device (Hardware Design)

This repository contains the hardware design files (Altium Designer) for a Photoplethysmography (PPG) sensor hand-held device. This project was developed as part of a research initiative aimed at improving signal quality from PPG sensor for wearable health monitoring.

## Project Overview

The system is divided into two main modules:
1.  **PPG Sensor Board**: Optical PPG sensor components.
2.  **Processing Board (PPG_process_v2)**: Main controller board responsible for signal acquisition, data processing, power management, and communication.

## System Architecture

### 1. Processing Unit
- **MCU**: ESP32 (Wi-Fi/Bluetooth enabled microcontroller)
- **Power Management**: Dedicated power supply circuits
- **Key Schematics**: `ESP32.SchDoc`, `POWER_SUPPLY.SchDoc`

### 2. Analog Front-End (AFE) & Driver
- **LED Driver**: Current regulation for optical components (`DRIVER_LED&AFE.SchDoc`)
- **Signal Conditioning**: Filtering and amplification for PPG signals

## CAD Tools Used
- **PCB Design**: Altium Designer
- **Schematic Capture**: Altium Designer

## Directory Structure
- `PPG_process_v2/`: Files related to the main processing unit, analog front-end and power supply.
- `PPG_sensor/`: Files related to the optical PPG sensors.

## Visuals
Add screenshots of your 3D PCB View and Schematic here. Visuals are crucial for Hardware GitHub repos.

## Usage
These files can be opened and edited using Altium Designer.

## License
MIT 
