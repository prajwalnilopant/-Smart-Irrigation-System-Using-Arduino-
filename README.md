# -Smart-Irrigation-System-Using-Arduino-

# Smart Irrigation System using Arduino

This project implements a smart irrigation system using Arduino, which utilizes a soil moisture sensor to monitor the moisture level of the soil and control a water pump accordingly. The system ensures efficient water usage by only activating the pump when the soil moisture is below a certain threshold.

## Table of Contents

- [Introduction](#introduction)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)


## Introduction

The Smart Irrigation System is designed to automate the watering process for plants. By continuously monitoring the soil moisture levels, the system can determine when the soil is dry and needs watering, and it will activate a water pump to irrigate the plants. This helps in conserving water and ensures that plants receive the right amount of water.

## Hardware Requirements

- Arduino board (e.g., Arduino Uno)
- Soil moisture sensor
- Water pump (or an LED for simulation)
- Jumper wires
- Breadboard (optional)

## Software Requirements

- Arduino IDE

## Setup and Installation

1. **Connect the soil moisture sensor:**
   - Connect the VCC pin of the sensor to the 5V pin of the Arduino.
   - Connect the GND pin of the sensor to the GND pin of the Arduino.
   - Connect the analog output pin of the sensor to the A0 pin of the Arduino.

2. **Connect the water pump (or an LED for simulation):**
   - Connect one end of the pump/LED to pin 4 of the Arduino.
   - Connect the other end of the pump/LED to the GND pin of the Arduino.

3. **Install the Arduino IDE:**
   - Download and install the Arduino IDE from the [official website](https://www.arduino.cc/en/software).

4. **Upload the code:**
   - Copy the provided code into the Arduino IDE.
   - Connect your Arduino board to your computer using a USB cable.
   - Select the appropriate board and port from the Tools menu.
   - Upload the code to your Arduino board.

## Usage

1. **Power the Arduino:** Ensure the Arduino board is powered either through a USB connection to your computer or an external power source.
2. **Monitor the Serial Output:** Open the Serial Monitor from the Arduino IDE to view the soil moisture readings.
3. **Observe the Water Pump/LED:** The water pump (or LED) will be activated when the soil moisture level drops below the threshold.

