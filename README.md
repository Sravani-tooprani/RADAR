# RADAR PROJECT

# **Overview**

## **Introduction**  
The RADAR Project is focused on developing and testing Advanced Driver Assistance Systems (ADAS) leveraging automotive radar technology. This project aims to enhance vehicle safety features such as Adaptive Cruise Control (ACC), Blind Spot Detection (BSD), and Automatic Emergency Braking (AEB).

---

## **Project Objectives**  
- Develop and validate radar sensor functionalities for ADAS.  
- Ensure compliance with automotive safety and communication standards.  
- Automate testing processes for enhanced efficiency and accuracy.  

---

## **Key Features and Modules**  
### 1. **ADAS Systems Overview**  
- Understanding and implementing Adaptive Cruise Control (ACC).  
- Lane Departure Warning and Blind Spot Detection using radar data.  
- Integration of radar modules with vehicle Electronic Control Units (ECUs).  

### 2. **Radar Test Bench Setup**  
- **Without XCP**: Basic test bench configuration using CAN and Ethernet for data acquisition.  
- **With XCP**: Enhanced test environment with real-time measurement and calibration capabilities using Vector CANape.  

### 3. **Flashing and Debugging**  
- **CANape Flashing**: ECU flashing for radar firmware updates and parameter calibration.  
- **Trace32 Debugger Flashing**: Low-level microcontroller flashing and debugging using JTAG interfaces.  

---

## **Software and Tools Used**  
- **Vector CANape** – For measurement, calibration, and flashing.  
- **Lauterbach Trace32** – Debugger for low-level microcontroller programming.  
- **dSPACE and CANoe** – For simulation and testing in HIL (Hardware-in-the-Loop) setups.  

---
## **BSW and ASW Modules**  

### 1. **BSW (Basic Software) Modules** 
## **BSW CD Module**
  
### 1. **10 SID Requirement Analysis and Testing**  
- Requirement analysis, test case design, execution, and reporting for 10 SID functionalities.  

### 2. **11, 28, 14, 19 SID Analysis and Execution**  
- Comprehensive analysis and test execution for multiple SIDs to ensure functional safety and compliance.  

### 3. **31 SID and EOL Proxy**  
- End-of-line (EOL) testing for radar system integrity and final validation before deployment.  

### 4. **Defect Life Cycle Management**  
- **Defect Ticket Creation** – Identifying and documenting defects.  
- **Rejected Defect Handling** – Analyzing and justifying rejected tickets.  
- **Defect Life Cycle** – Tracking defect status from discovery to resolution.  

---

 
## **BSW COM Module** 
– Understanding and implementing communication protocols.  

## **Automation and Network Management**  
### 1. **Automation**  
- **Indicator Project Automation** – Streamlining indicator testing.  
- **Radar Message Periodicity Check** – Ensuring timely message transmission and validation.  
- **Radar Tx Signals** – Initial value checks and Min-Max range automation.  

### 2. **Network Management (NM)**  
- **NM State Diagram and Requirements** – Understanding state transitions and signal requirements.  

### 3. **Calibration and Signal Validation**  
- **Calibration Protocol** – Understanding the parameter tuning and calibration process.  
- **A2L and A2L Loading** – Managing calibration files and validating signal values.  

---
## **BSW FM (Fault Management)** 
– Managing Diagnostic Trouble Codes (DTCs) and Event Counters.  

### 2. **ASW (Application Software) Modules**  
- **Adaptive Cruise Control (ACC)** – State machine implementation and testing.  
- **ACC States and APC/SOC Conditions** – Handling transitions and safety checks.  

---

## **HIL Testing and Simulation**  
- **HIL Car Maker Integration** – Simulation of real-world driving scenarios.  
- **Testing Concepts** – Applying HIL-based validation for radar functionalities and ADAS features.  

---
