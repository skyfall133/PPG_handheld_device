# PPG Sensor & Processing Device (Hardware Design)

This repository contains the hardware design files (Altium Designer) for a Photoplethysmography (PPG) sensor hand-held device. This project was developed as part of a research initiative aimed at improving signal quality from PPG sensor for wearable health monitoring.

## Project Structure

The hardware design is divided into two primary modules:

### 1. Processing Board (`PPG_processing/`)
The main logic and power management board.
- **Microcontroller**: ESP32 (Wi-Fi/Bluetooth enabled MCU)
- **Key Schematics**: 
  - `ESP32.SchDoc`: Microcontroller and IO setup.
  - `DRIVER_LED&AFE.SchDoc`: AFE4490 and LED current control.
  - `POWER_SUPPLY.SchDoc`: Voltage regulation.
- **PCB Layout**: `PPG_board.PcbDoc`
- **Project File**: `PPG_process_v2.PrjPcb`

### 2. PPG Sensor Board (`PPG_sensor/`)
The optical interface module.
- **Key Files**: `PPG_sensor.SchDoc`, `PPG_sensor.PcbDoc`
- **Project File**: `PPG_sensor.PrjPcb`

## Tools Used
- **EDA Tool**: Altium Designer

## Visuals
> - A 3D view screenshot of the PCB_processing and PPG_sensor:
<img width="1257" height="746" alt="image" src="https://github.com/user-attachments/assets/e926dd8d-e196-4c8b-9b27-7a7c6c885f2c" />
<img width="1081" height="744" alt="image" src="https://github.com/user-attachments/assets/10f4f6cb-022e-4b3e-893c-e012070cb70d" />


## How to Use
1. Clone the repository.
2. Open the project file:
   - `PPG_processing/PPG_process_v2.PrjPcb` for the main board.
   - `PPG_sensor/PPG_sensor.PrjPcb` for the sensor board.
3. Use Altium Designer to view/edit.

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
