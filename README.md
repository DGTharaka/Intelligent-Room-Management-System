# Intelligent Room Management System

🚀 **Project Overview**

As part of our 2nd-year Electrical Engineering coursework at the University of Moratuwa, my team and I developed an **Intelligent Room Management System** aimed at optimizing energy efficiency and environmental comfort in conference rooms and lecture halls.

![Group Photo](Group_Photo.jpg)

---

## Project Highlights

### 🎯 **Objective**
The project focuses on automating fan speed and light intensity based on real-time sensor data, reducing energy waste, and improving room comfort.

### 🔹 **Sensors Used**
- **LM35 Temperature Sensor**: Measures room temperature and adjusts fan speed accordingly.
- **LDR (Light Dependent Resistor)**: Monitors ambient light to control room lighting.
- **Custom Occupancy Detection**: We built a sensor using two laser beams and two LDRs in a bridge voltage configuration. This detects when people enter or exit the room, ensuring that lights and fans only operate when needed.

---

## Control Logic

### 🔧 **Key Features**
- **Fan Speed Control**: Adjusts based on temperature readings using custom PWM-like logic implemented in LabVIEW. Instead of a standard PWM signal, we varied the off-time of the fan in software to control speed.
- **Light Control**: Automatically adjusts light intensity based on the amount of natural light detected by the LDR.
- **Occupancy-Based Control**: Lights and fan automatically switch off when the room is unoccupied.

![Intelligent Room Management System](Intelligent_Room_Management_System.jpg)

---

## Physical Implementation

We created a model of the room using Styrofoam boards to demonstrate the effectiveness of our control system. This setup allowed us to simulate real-world conditions and fine-tune the automation logic.

![Physical Arrangement](Physical_Arrangement.jpg)

---

## LabVIEW Program

We used LabVIEW and DAQmx functions for sensor data acquisition and control logic implementation. Our decision to generate a PWM-like signal directly in LabVIEW was key to staying within the software environment while achieving the desired control.

![LabVIEW Programme](LabVIEW_Programme.png)

---

## Key Takeaways

- **Energy Efficiency**: The system ensures that no energy is wasted when the room is unoccupied or when natural light is sufficient.
- **Automation**: The system runs autonomously, reducing the need for manual intervention and ensuring optimal environmental conditions.
- **Custom PWM-Like Signal**: Our solution highlights the creative use of LabVIEW to simulate a PWM signal without using external controllers.

---

## Future Exploration

We’re eager to explore further advancements in automation and control systems, and how these technologies can be applied to other areas of energy management and environmental control.

---

## Connect with Us

Feel free to reach out if you’re interested in discussing the project or exploring potential collaborations!

---

#ElectricalEngineering #Automation #SmartSystems #EnergyEfficiency #ControlSystems #LabVIEW #UniversityOfMoratuwa
