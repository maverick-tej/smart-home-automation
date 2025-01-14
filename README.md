# IoT-Based Home Automation System

This project implements an IoT-based home automation system using Flask and Raspberry Pi. It allows users to control multiple relays (e.g., lights, fans, and an AC) via a web interface. The system also provides real-time updates on hardware states.

---

## Features

- Control up to 10 relays (R1–R10) and an AC through a web interface.
- User authentication for secure access.
- Real-time hardware state updates.
- Designed for Raspberry Pi GPIO control.

---

## Technologies Used

- **Python**: Flask framework for the web interface and API.
- **Hardware**: Raspberry Pi, GPIO pins, relays.
- **HTML**: Templates for the web interface.

---

## Hardware Requirements

- Raspberry Pi (any model with GPIO support).
- 10-channel relay module.
- AC appliances like lights and fans.
- Jumper wires for connections.
- Power supply for the Raspberry Pi and relays.

---

## Software Requirements

- Python 3.x
- Flask
- RPi.GPIO library (for GPIO pin control)

---

## Circuit Diagram

Include a diagram showing the connections between:
- Raspberry Pi GPIO pins.
- Relays and appliances.

---

## Setup Instructions

### Clone the Repository:
```bash
git clone https://github.com/your-username/iot-home-automation.git
cd iot-home-automation
