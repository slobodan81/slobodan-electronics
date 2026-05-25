# BIOROWER Rowing Machine Sensor Testing – Embedded Tech

**Company:** Embedded Tech  
**Focus:** Strain Gauge Calibration & Testing Automation  
**Technology:** Relay Logic, Motor Control, 3D Printing

---

## Project Overview

One of my most interesting and challenging projects involved developing an **automated strain gauge testing and calibration system** for rowing machine sensors. The goal was to transform a manual, time-consuming calibration process into an efficient, automated testing system.

## The Challenge

### Original Manual Process
- **Calibration Machine**: Manually operated to pull oar up to 80kg
- **User Workflow**: 
  1. Pull oar to 10, 20, 30, 50, 70, 80kg
  2. Write down values from rower application
  3. Application calculates sensor coefficients
- **Quality Testing Requirement**: Each sensor must be tested under load for 30-180 minutes with coefficients remaining stable
- **Problem**: Manual testing required extensive physical effort (rowing all day) for quality assurance

### Key Issues
- ⚠️ Extremely time-consuming for production quality control
- ⚠️ Manual labor intensive
- ⚠️ Inconsistent testing conditions
- ⚠️ Poor scalability for high production volumes

---

## Solution Implemented

I redesigned the calibration machine to function as an **automated testing system** using **relay logic** (inspired by old elevator control systems) combined with modern automation.

### System Architecture

#### 1. Control Logic
- **Old-style relay logic**: Proven, reliable automation method
- **Position switches**: Precise positioning control
- **Motor control**: Automated pull and release cycles

#### 2. Force Measurement
- **Digital scale**: Accurate weight measurement
- **Carabiners**: Force transfer mechanism
- **Position monitoring**: Ensures consistent force application

#### 3. Automated Cycles
- **Start position**: 1-2kg (motor reverses, pulls oar back)
- **End position**: 80kg (motor reverses, pulls oar forward)
- **Testing duration**: 30 to 180 minutes per sensor (fully automated)

#### 4. Mechanical Components
- **3D printed parts**: Custom fixtures using PET-G filament
- **Motor**: Controls oar movement
- **Position switches**: End-of-stroke and start-of-stroke detection
- **Mounting structure**: Integrated with existing calibration machine

---

## Design Highlights

### Automation Features
- ✅ **Continuous operation**: Runs unattended for extended periods
- ✅ **Consistent force profile**: Repeatable 1-80kg cycles
- ✅ **Programmable duration**: 30-180 minute test runs
- ✅ **Reliable control**: Proven relay logic technology

### 3D Printed Components
- Custom fixture design using CAD
- PET-G filament for durability and strength
- Optimized for repetitive mechanical stress
- Easy to modify for different sensor types

### Force Control System
- Precision digital scale for accurate measurement
- Carabiner connection for safe force transfer
- Mechanical switches for position feedback
- Smooth force ramp-up to prevent shock loading

---

## Results & Benefits

### Before Automation
- ❌ Manual rowing required for each sensor
- ❌ 30-180 minutes per sensor (manual labor)
- ❌ Inconsistent test conditions
- ❌ Limited testing capacity
- ❌ Operator fatigue

### After Automation
- ✅ **Eliminated manual rowing**: Fully automated cycles
- ✅ **Consistent conditions**: Repeatable force profiles
- ✅ **24/7 operation**: Run overnight and unattended
- ✅ **Faster validation**: Quick sensor quality assessment
- ✅ **Reliable results**: Standardized testing procedure
- ✅ **Scalable solution**: Test multiple sensors simultaneously

---

## Technical Specifications

| Component | Specification |
|-----------|---------------|
| **Control System** | Relay Logic |
| **Force Range** | 1-80 kg |
| **Force Measurement** | Digital Scale |
| **Motor Control** | Automated forward/reverse |
| **Position Switches** | End-of-stroke detection |
| **Test Duration** | 30-180 minutes (programmable) |
| **3D Printed Parts** | PET-G filament |
| **Testing Capacity** | Unattended continuous operation |

---

## Key Innovations

1. **Relay-Based Automation**: Simple, reliable control without complex electronics
2. **3D Printed Fixtures**: Custom parts designed for this specific application
3. **Unattended Operation**: Extended test cycles without manual intervention
4. **Scalable Design**: Can test multiple sensors in parallel with additional units

---

## Project Impact

- **Efficiency**: Reduced testing time from manual hours per sensor to unattended automated cycles
- **Quality**: Standardized testing ensures consistent sensor quality
- **Cost**: Eliminated labor costs for quality assurance testing
- **Scalability**: Enabled production scaling without proportional increase in testing resources

---

## Related Documentation

- Mechanical design: [To be added]
- Relay circuit diagrams: [To be added]
- 3D CAD models: [To be added]
- Test procedures: [To be added]

---

*Project Type: Manufacturing Automation & Quality Control*
