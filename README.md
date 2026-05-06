# Real-Time Drunk Driver Test Structure Design and Execution with Entrance Restriction

## Published Research Paper

This research paper presents a real-time drunk driver detection and vehicle entry restriction system designed using Arduino Uno and multiple embedded sensors. The system automatically prevents vehicle access when alcohol is detected, helping improve road safety and accident prevention.

The paper has been officially published in the:

**Proceedings of the 6th Annual Paper Meet (IEB-EE APM2025)**  
Electrical Engineering Division (EED), IEB, Ramna, Dhaka, Bangladesh  
December 2025 :contentReference[oaicite:0]{index=0}

---

## ResearchGate Publication

🔗 **ResearchGate Link:**  
https://www.researchgate.net/publication/398689594_Real-Time_Drunk_Driver_Test_Structure_Design_and_Execution_with_Entrance_Restriction

---

## Abstract

This project introduces a real-time automated drunk driver detection and vehicle entry restriction system. The system uses an Arduino Uno microcontroller along with an MQ-3 alcohol sensor, IR proximity sensor, mini brushless fan, servo motor, buzzer, and LCD display.

When a vehicle is detected, the system collects breath samples and checks alcohol concentration. If alcohol is detected above the threshold level, the gate remains closed and an alert buzzer is activated. Otherwise, the gate opens automatically for vehicle access.

The proposed system is:
- Low-cost
- Reliable
- Real-time
- Fully automated
- Suitable for parking areas, checkpoints, and industrial facilities

---

# System Features

✅ Real-time alcohol detection  
✅ Automatic gate barrier control  
✅ LCD monitoring system  
✅ Audio alert system using buzzer  
✅ Vehicle presence detection  
✅ Low-cost hardware implementation  
✅ Arduino-based embedded system  

---

# Hardware Components

| Component | Purpose |
|---|---|
| Arduino Uno | Main controller |
| MQ-3 Alcohol Sensor | Alcohol detection |
| IR Proximity Sensor | Vehicle detection |
| Servo Motor | Gate control |
| 16×2 LCD I2C Display | System status display |
| Buzzer | Warning alert |
| Brushless DC Fan | Breath sample collection |
| Rechargeable Battery | Portable power supply |

---

# System Workflow

1. Vehicle enters detection zone  
2. IR sensor detects vehicle presence  
3. Fan collects breath sample  
4. MQ-3 sensor checks alcohol level  
5. If alcohol detected:
   - Access denied
   - Gate remains closed
   - Buzzer activates
6. If no alcohol detected:
   - Access granted
   - Gate opens automatically

---

# Research Contributions

- Developed a cost-effective drunk driving prevention system
- Implemented both simulation and hardware prototype
- Integrated automated vehicle entry restriction
- Improved reliability using multiple sensor checks
- Demonstrated real-time embedded safety monitoring

---

# Authors

- Tinjilur Rahman Fahim
- Sabbir Hossain
- Marin Rahman
- MD. Rafidul Islam
- Muhibul Haque Bhuyan

---

# Technologies Used

- Arduino IDE
- Embedded Systems
- Proteus Simulation
- MQ-3 Alcohol Sensor
- Servo Automation
- IoT-based Safety Concepts

---

# Repository Contents

```text
paper/
├── APMEE-25-661.pdf

arduino_code/
├── main.ino

images/
├── hardware_setup.jpg
├── simulation_result.png
├── flowchart.png
