# Portfolio - Slobodan Perić

Welcome to my electronics portfolio! Here you'll find examples of schematics, PCB designs, and 3D models from my professional projects and hobby work. I've designed solutions for various companies and also created semi-professional equipment used in music production.

---

## 📋 Projects

### 1. 🔌 Kit Main Board V2.0 (ESP32) – Invenda Solutions
**Status:** Current Project  
**Company:** Invenda Solutions  
**Year:** Present

#### Project Overview
One of my latest projects, developed in cooperation with a firmware colleague, is the **Kit Main Board** used for vending machine control. This board serves as the central controller for advanced vending machine management.

#### Key Responsibilities & Features
- **Current Measurement**: Measures current of cooling unit compressor, fans, and cooling pump
- **Temperature Monitoring**: Measures crucial internal machine temperatures with indication and alerts
- **Motor Control**: Controls and runs all delivery motors
- **Cooling System Management**: Controls the cooling unit
- **Status Monitoring**: Checks door and drop sensor status
- **Communication**: Interfaces with PC and payment devices
- **Payment Integration**: MDB converter implemented on PCB for payment device control

#### Technical Specifications
- **Microcontroller**: ESP32 (upgraded from older Atmega128 versions)
- **Power Management**: Step-down converter from 24VDC to 5VDC and 3.3VDC
- **Current Sensing**: HAL sensors measuring -10 to 10A range
- **Communication Interfaces**: MDB, LAN (with 0R resistors for prototyping flexibility), USB
- **I/O Connections**: Drop sensor, door indicator, motor outputs/senses, temperature probes

#### Board Variations
Due to confidentiality constraints (prototype board photos unavailable), I developed three complementary boards:
- **Current Sensing Board**: Specialized current measurement module
- **MDB Converter Board**: Payment device interface (collaborated with colleague)
- **Universal Board**: Atmega128-based variant for legacy compatibility

#### Status
The board is in the final phase of testing and will be released soon.

**📁 [View Project Details](./projects/01-kit-main-board-esp32/README.md)**

---

### 2. 🚣 BIOROWER Rowing Simulation Machine Sensor Testing – Embedded Tech
**Company:** Embedded Tech  
**Focus:** Strain Gauge Calibration & Testing

#### Project Overview
One of my most interesting projects involved developing a **strain gauge testing and calibration system** for rowing machine sensors. The challenge was to automate the sensor quality testing process, which traditionally required manual labor.

#### The Challenge
- Original calibration: Manual operation, pulling oar up to 80kg
- User workflow: Pull oar to 10, 20, 30, 50, 70, 80kg, record readings
- Quality testing requirement: Each sensor must be tested under load for 30-180 minutes to verify coefficient stability
- **Problem**: Manual testing was extremely time-consuming and inefficient

#### Solution Implemented
I redesigned the calibration machine using **old relay logic** (similar to elevator control systems) to automate the testing process.

#### Key Components
- **Calibration Equipment**: Digital scale with carabiners for force measurement
- **Automated Control**: Position switches at 80kg (direction change) and 1-2kg (return position)
- **Motor Control**: Automated motor for pulling and releasing the oar
- **3D Printed Parts**: Custom fixtures using 3D printing with PET-G filament
- **Testing Duration**: 30 to 180 minutes per sensor (fully automated)

#### Results
- ✅ Eliminated manual rowing during testing
- ✅ Consistent and repeatable test conditions
- ✅ Faster sensor validation
- ✅ Reliable quality control

**📁 [View Project Details](./projects/02-biorower-sensor-testing/README.md)**

---

### 3. 🚴 WATTBIKE Boards Testing Equipment – Embedded Tech
**Company:** Embedded Tech  
**Focus:** Electronic Board Test Systems

#### Project Overview
I created comprehensive testing equipment for Wattbike's electronic control boards. Each Wattbike includes multiple electronic components that required individual test devices simulating real operational conditions.

#### Wattbike System Components Tested
- **Electronic Brake**: Simulates uphill driving resistance
- **Strain Gauge**: Measures user pedaling force
- **BLE Communication**: Bluetooth Low Energy connectivity
- **Display**: User interface

#### Test Equipment Developed

1. **Power Board for Braking Control**
   - Tests electronic brake functionality
   - Simulates load conditions

2. **Power Supply Tester**
   - Input: 20 – 120VAC
   - Output: 12V 500mA
   - Validates power regulation and stability

3. **Monitor Board Voltage Tester**
   - Tests display board voltage levels
   - Ensures proper regulation

4. **Sensor Board Tester**
   - Validates strain gauge interface
   - Tests BLE communication
   - Confirms sensor data integrity

#### Testing Approach
Each test device simulates the exact conditions encountered in real Wattbike operation, ensuring quality and reliability before deployment.

**📁 [View Project Details](./projects/03-wattbike-testing-equipment/README.md)**

---

## 🎯 Skills Demonstrated

- **PCB Design**: Schematic capture, layout, and manufacturing
- **Microcontrollers**: ESP32, Atmega128, embedded systems
- **Analog Electronics**: Current sensing, power management, signal conditioning
- **Power Electronics**: Step-down converters, voltage regulation
- **Communication Protocols**: MDB, LAN, USB, BLE
- **Testing & Automation**: Test equipment design, calibration systems
- **3D Modeling & Printing**: Prototype development with PET-G
- **Firmware Collaboration**: Working with firmware teams
- **Problem Solving**: Custom solutions for complex requirements

---

## 📁 Repository Structure

```
slobodan-electronics/
├── README.md (this file)
├── projects/
│   ├── 01-kit-main-board-esp32/
│   │   ├── README.md
│   │   ├── images/
│   │   └── documents/
│   ├── 02-biorower-sensor-testing/
│   │   ├── README.md
│   │   ├── images/
│   │   └── documents/
│   └── 03-wattbike-testing-equipment/
│       ├── README.md
│       ├── images/
│       └── documents/
```

---

## 📎 Future Projects

More projects coming soon! I plan to add additional portfolio items and hobby projects as they're ready.

---

## 📧 Contact & More Information

For more details about these projects or to discuss potential collaborations, feel free to reach out!

---

*Last Updated: May 2026*
