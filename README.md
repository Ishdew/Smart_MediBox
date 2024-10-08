# Smart Medi Box


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Overview](#project-overview)
- [Hardware Setup](#hardware-setup)
- [Software Components](#software-components)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Smart Medi Box is an innovative medication management and monitoring system designed to enhance patient care by providing a comprehensive solution for medication management and timely reminders. This project leverages the ESP32 microcontroller and incorporates various functionalities to ensure safe medication storage and administration.

## Features

- **Medication Reminders:** Remind the user to take medicine at time through alarms.
- **Secure Storage:** Safely store medications and prevent unauthorized access.
- **Inventory Tracking:** Keep track of medication inventory.
- **Remote Monitoring:** keep medicine in the required conditions via monitoring temperature and humidity continously and notifying the user if there is a bad condition.


## Technologies Used

The Medi Box project relies on the following technologies and tools:

- **ESP32 Devkit V1:** The core hardware platform for building the system.
- **Arduino:** Used for programming the ESP32 microcontroller.
- **EasyEDA:** Design and PCB layout tool for creating custom circuits.
- **Node-Red:** A flow-based development tool for IoT applications.
- **MQTT:** Lightweight messaging protocol for communication between components.


## Project Overview

The project aims to improve patient care by ensuring the correct and timely administration of medications. Key aspects of the project include:

- **Hardware Development:** Design and build a hardware system using the ESP32 microcontroller.
- **Secure Medication Storage:** Implement mechanisms for secure medication storage.
- **Medication Reminders:** Set up medication reminders based on the patient's schedule.
- **Remote Monitoring:** Enable remote monitoring and notifications for healthcare providers or family members.

## Wokwi Simulation for Hardware Setup
<img src="Wokwi Screenshot.png" alt="README Template" />



## Software Components

The software components of the Medi Box project include:

- **Arduino Firmware:** The firmware running on the ESP32 microcontroller.
- **Node-Red Flows:** Node-Red flows for medication scheduling and notifications.

<img src="Flow_Screenshot.png" alt="README Template" />

## Usage

1. **Hardware Assembly:** According to Wokwi simulation assemble the hardware components.
2. **Programming:** Flash the Arduino firmware onto the ESP32 microcontroller.
3. **Node-Red Configuration:** Configure Node-Red flows for medication scheduling and notifications.
4. **Medication Management:** Use the user-friendly interface to manage medications and set up reminders.
5. **Remote Monitoring:** Monitor medication adherence and receive notifications remotely.


# Contribute

Contributions are always welcome!

## License :pencil:

This project is licensed under [MIT](https://opensource.org/licenses/MIT) license.

## Show your support 🙏

Give a ⭐️ if this project helped you!