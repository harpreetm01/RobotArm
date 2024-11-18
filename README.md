# Robot Arm 

This repository contains the code, documentation, and resources for a palletizing robot arm project based on the design by [Florin Tobler](https://www.thingiverse.com/thing:1718984?collect). The project involves building and programming a robot arm capable of palletizing objects in a warehouse or industrial setting.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Set-up](#set-up)
- [Usage](#usage)
- [Credits](#credits)


## Introduction

This project is a palletizing robot arm based on a project guide by [Florin Tobler](https://www.thingiverse.com/thing:1718984?collect) from Thingiverse. It is designed to automate the process of palletizing objects or materials, improving efficiency and reducing manual labor. The project combines mechanical design, electronics, and programming to create a functional robot arm capable of performing the required tasks.

![](RoboArm/Photos/16.jpg)

## Requirements

- Arduino Uno or compatible microcontroller board
  - Servo motors for the robot arm
  - NEMA17 Step Motors
- Sensors for object detection (e.g., ultrasonic, infrared)
- Programming language: C++ for Arduino sketches
- Arduino IDE or compatible development environment

## Set-up

To set up and use the palletizing robot arm project, follow the steps below:

### Software Setup

- Download and install "Universal Gcode Sender" from the official website. It is a software tool used to send G-code commands to the robot arm.
  - Official Website: [Universal Gcode Sender](https://universalgcodesender.com/)

### Firmware Setup

- Download the GRBL firmware source code from the official repository.
  - Official Repository: [GRBL on GitHub](https://github.com/grbl/grbl)
- Open the GRBL firmware source code in the Arduino IDE.
- Select the appropriate board and port in the Arduino IDE and Upload the GRBL firmware to the Arduino board.
  - Refer to the Arduino documentation if you need guidance on uploading firmware

### Calibrating the Robot Arm

- Power on the robot arm and connect it to your computer using a USB cable.
- Open "Universal Gcode Sender" on your computer.
- Connect "Universal Gcode Sender" to the robot arm by selecting the appropriate port.
- Configure the settings for the robot arm, such as motor steps, acceleration, and travel limits.
  - Consult the provided documentation or the original project guide for recommended settings.
- Calibrate the robot arm by running the calibration routines provided by the GRBL firmware.
  - Consult the GRBL documentation or the original project guide for instructions on calibrating the robot arm.

## Usage

- Open "Universal Gcode Sender" on your computer.
- Connect to the robot arm by selecting the appropriate port.
- Load the G-code file that contains the instructions for the robot arm.
- Execute the G-code commands to operate the robot arm.
  - Refer to the documentation or the original project guide for examples and instructions on creating and executing G-code commands.

## Credits

This project is based on the [Project Guide](provide_link_to_original_guide) created by [Florin Tobler](https://github.com/ftobler) on Thingiverse. I express my gratitude to them for their valuable contribution.
