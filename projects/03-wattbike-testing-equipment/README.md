# WATTBIKE Boards Testing Equipment – Embedded Tech

**Company:** Embedded Tech  
**Focus:** Electronic Board Test Systems  
**Application:** Performance Cycling Bikes

---

## Project Overview

I created a comprehensive suite of **testing equipment for Wattbike's electronic control boards**. Each Wattbike includes multiple interconnected electronic systems that require rigorous validation. I developed individual test devices for each board, each simulating real operational conditions to ensure quality and reliability.

## System Overview

A complete Wattbike system includes:
- 🔌 **Power Board**: Electronic brake control
- 📊 **Monitor Board**: User interface and display
- 🔋 **Sensor Board**: Pedal force measurement and BLE communication
- ⚡ **Power Supply**: Input power conditioning

---

## Test Equipment Developed

### 1. 🔌 Power Board for Braking Control

#### Purpose
Tests the electronic brake system that simulates resistance during cycling (uphill simulation).

#### Testing Functions
- Validates brake control signals
- Tests electromagnetic coil activation
- Measures torque application consistency
- Simulates realistic load conditions
- Verifies response time and stability

#### Key Capabilities
- Progressive load application (0-100%)
- Real-time monitoring of brake parameters
- Safety interlocks for operator protection
- Reproducible test scenarios

---

### 2. ⚡ Power Supply Tester

#### Purpose
Validates the power supply board's ability to accept and regulate variable input voltages.

#### Specifications
- **Input Voltage Range**: 20V – 120V AC
- **Output**: 12V DC, 500mA
- **Testing Parameters**:
  - Voltage regulation accuracy
  - Load stability
  - Thermal behavior
  - Input filtering effectiveness

#### Test Scenarios
- ✅ Minimum voltage operation (20VAC)
- ✅ Nominal operation (standard AC input)
- ✅ Maximum voltage operation (120VAC)
- ✅ Load transient response
- ✅ Short circuit protection
- ✅ Thermal stability

#### Validation Checks
- Output voltage stability
- Current limiting functionality
- Heat dissipation
- Protection mechanism engagement

---

### 3. 📊 Monitor Board Voltage Tester

#### Purpose
Ensures display board voltage regulation and functionality across all operating conditions.

#### Testing Functions
- Validates voltage levels on all bus rails
- Monitors power distribution
- Tests under-voltage and over-voltage conditions
- Verifies display driver supply stability
- Measures power consumption

#### Test Parameters
- Supply voltage levels
- Noise and ripple measurement
- Load regulation
- Transient response
- Brownout behavior

#### Validation Checks
- ✅ Correct voltage at display connectors
- ✅ Stable supply under variable loads
- ✅ Proper brownout detection
- ✅ Safe shutdown sequence

---

### 4. 🔋 Sensor Board Tester

#### Purpose
Validates the complete sensor and communication system including pedal force measurement and BLE connectivity.

#### Key Components Tested
- **Strain Gauge Interface**: Force measurement accuracy
- **BLE Communication**: Bluetooth Low Energy connectivity
- **Signal Conditioning**: Analog signal processing
- **Microcontroller**: Sensor data processing
- **Firmware**: Correct operation and response

#### Testing Functions
- Strain gauge linearity and accuracy
- Force measurement calibration
- BLE pairing and connection
- Data transmission integrity
- Signal-to-noise ratio verification
- Bluetooth range and stability

#### Test Scenarios
- ✅ Zero-force baseline
- ✅ Progressive force application (0-300W equivalent)
- ✅ BLE connection establishment
- ✅ Real-time data streaming
- ✅ Connection robustness
- ✅ Firmware response to force changes

#### Validation Parameters
- Measurement accuracy
- Data transmission rate
- Connection stability
- Signal integrity
- Power consumption during BLE operation

---

## Testing Approach

### Real-World Simulation
Each test device replicates the exact conditions encountered in actual Wattbike operation:
- Realistic force ranges
- Actual electrical loads
- BLE communication in various environments
- Extended operation cycles

### Quality Assurance Benefits
- ✅ **Consistency**: Standardized testing procedure
- ✅ **Reliability**: Early detection of defects
- ✅ **Performance**: Validates real-world performance
- ✅ **Safety**: Ensures user safety in all conditions
- ✅ **Traceability**: Complete test documentation

---

## Test Equipment Summary

| Test Equipment | Input | Output | Primary Focus |
|----------------|-------|--------|----------------|
| **Power Board Tester** | Variable brake signals | Torque measurement | Brake functionality |
| **Power Supply Tester** | 20-120VAC | 12VDC, 500mA | Voltage regulation |
| **Monitor Tester** | Variable supply voltage | Display supply voltage | Power distribution |
| **Sensor Board Tester** | Variable force inputs | BLE data stream | Sensor & comms |

---

## Integration Testing

These test systems work together to validate the complete Wattbike electronics ecosystem:
1. **Power Supply** provides clean power to all boards
2. **Power Board** controls resistance based on firmware commands
3. **Sensor Board** measures user input and communicates via BLE
4. **Monitor Board** displays user data and status

---

## Key Achievements

- ✅ Comprehensive testing coverage of all electronic subsystems
- ✅ Real-world condition simulation
- ✅ Reliable quality assurance process
- ✅ Early defect detection capability
- ✅ Reproducible test results
- ✅ Scalable for production testing

---

## Related Documentation

- Power board schematic: [To be added]
- Supply tester specification: [To be added]
- Monitor board test report: [To be added]
- Sensor board calibration procedure: [To be added]
- BLE test protocol: [To be added]

---

*Project Type: Electronic Test & Validation Equipment*
*Application: Performance Cycling Equipment Quality Assurance*
