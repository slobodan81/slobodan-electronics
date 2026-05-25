# Kit Main Board V2.0 (ESP32) – Invenda Solutions

**Status:** Current Project  
**Company:** Invenda Solutions  
**Year:** Present  
**Microcontroller:** ESP32

---

## Project Overview

The **Kit Main Board V2.0** is a comprehensive control board designed for advanced vending machine management. Developed in cooperation with a firmware colleague, this board serves as the central hub controlling all critical vending machine functions.

## Key Features

### 🔋 Power Management
- **Step-down converter**: 24VDC → 5VDC and 3.3VDC
- Efficient power distribution for all subsystems
- Protection and regulation circuits

### 📊 Current Measurement
- **HAL Current Sensors**: -10A to +10A range
- Measures current of:
  - Cooling unit compressor
  - Fans
  - Cooling pump
- Direct signal routing to ESP32 (no ADC needed)

### 🌡️ Temperature Monitoring
- Multiple temperature sensors for:
  - Internal machine temperature monitoring
  - Crucial system parameters
- Real-time indication and alerts

### 🎮 Motor Control
- Controls all delivery motors
- Manages cooling unit operation
- Multiple output drivers for various loads

### 📡 Communication Interfaces
- **MDB Converter**: Payment device control and communication
- **LAN**: Network connectivity with 0R resistors for prototyping flexibility
- **USB**: Programming and host communication

### 🔐 Safety & Status Monitoring
- Door sensor input monitoring
- Drop sensor status checking
- System status indicators

---

## Technical Specifications

| Parameter | Specification |
|-----------|---------------|
| **Microcontroller** | ESP32 |
| **Input Voltage** | 24VDC |
| **Output Voltages** | 5VDC, 3.3VDC |
| **Current Sensing Range** | -10A to +10A |
| **Communication** | MDB, LAN, USB |
| **Status** | Final phase testing |

---

## Board Variations

Due to confidentiality constraints on prototype hardware, three complementary boards were developed:

### 1. Current Sensing Board
- Specialized current measurement module
- HAL sensor integration
- Signal conditioning for ESP32

### 2. MDB Converter Board
- Payment device interface
- MDB protocol implementation
- Developed in collaboration with colleague

### 3. Universal Board
- Atmega128 microcontroller variant
- Legacy compatibility
- Alternative control option

---

## Design Highlights

### Step-Down Converter Section
Efficient power conversion from 24VDC to dual output voltages:
- 5VDC for I/O and peripherals
- 3.3VDC for microcontroller and sensors

### Current Sensing Circuitry
HAL sensor-based current measurement providing:
- Non-invasive current monitoring
- Direct ESP32 integration
- Simultaneous measurement of multiple loads

### Communication Architecture
Multiple communication channels enable:
- Real-time PC connectivity
- Payment system integration
- Network connectivity for remote management
- USB programming and debugging

### I/O Management
Comprehensive connections for:
- Drop sensor and door indicators
- Motor control outputs and feedback
- Temperature probe inputs
- Status and diagnostic signals

---

## Development Status

✅ **Current Phase**: Final Testing
- Board extensively tested in real-world vending machine environment
- Firmware integration complete
- All subsystems validated
- Ready for production release soon

---

## Next Steps

- Complete final production testing
- Manufacturing preparation
- Production release

---

## Related Documentation

- Schematic diagrams: [To be added]
- PCB layout: [To be added]
- 3D models: [To be added]
- Firmware documentation: [Link to firmware repo]

---

*Project Information: Current Phase of Development*
