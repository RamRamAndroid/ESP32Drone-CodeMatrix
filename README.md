## Introduction Of CodeMatrix ESP32 Drone
<img width="504" height="301" alt="drone" src="https://github.com/user-attachments/assets/26df250b-da77-4e9d-a287-f5f86218d446" />
<img width="301" height="301" alt="drone" src="https://github.com/user-attachments/assets/e4b2202e-be59-4bbd-b9b2-0febd59c7e95" />


CodeMatrix ESP32 Drone is a compact, WiFi-controlled drone based on the ESP32-S3 microcontroller. Designed for hobbyists, makers, and engineers, CodeMatrix ESP32 Drone offers a simple yet powerful platform for drone experimentation and development. It is an open-hardware project, making it easy to modify and expand.

Whether you’re new to drones or an experienced developer looking to create custom flight applications, LiteWing provides an accessible and affordable way to explore drone technology. Unlike traditional drones that require proprietary controllers, CodeMatrix ESP32 Drone connects to your smartphone, allowing for an intuitive flying experience without additional hardware.

The firmware on CodeMatrix ESP32 Drone supports Crazyflie cfclient and cflib, meaning you can program and control your drone using Python and add more features like height hold, position hold, gesture control, and more.

The latest version includes more GPIO pins, sensor mounts, LED indicators to make it easier to tinker with and program. The PCB frame design keeps it lightweight while reducing costs, making it one of the most affordable DIY drones available.

### Note:- The Files Related To The Drone Are In The Folder Named Drone


## Introduction Of CodeMatrix ESP32 Drone Positioning Module
<img width="504" height="301" alt="WhatsApp Image 2026-07-04 at 12 35 27 AM" src="https://github.com/user-attachments/assets/f35075ea-c3c8-4f26-9b4a-d3974b2d5326" />
<img width="301" height="301" alt="B-ezgif com-optimize (1)" src="https://github.com/user-attachments/assets/b045a87a-50e9-4dd1-b0eb-16f7d770a899" />

The ESP32 Drone Positioning Module is a plug-and-play optical flow and ToF-based stabilization add-on designed for indoor and GPS-denied flight. Featuring the PMW3901 optical flow sensor for precise X/Y position tracking and the VL53L1X Time-of-Flight sensor for accurate height measurement, this module enables stable height hold and position hold performance. Ideal for DIY drones, autonomous flight experiments, and educational robotics projects.

This module transforms your CodeMatrix ESP32 Drone and Litewing Drone into a fully-equipped autonomous flight platform by adding critical sensor capabilities: precision ToF height measurement, optical motion tracking, and visual status feedback. All connected through a 24-pin connector, eliminating complex wiring while maintaining robust electrical connections suitable for flight operations.

This add-on module is completely compatible with the CodeMatrix ESP32 Drone and LiteWing Drones and consists of the VL53L1x ToF sensor and PMW3901MB optical flow sensor for height hold and position hold, respectively. Apart from this, the module also has 4 Neopixel LEDs that can be programmed to indicate flight status or for visual appeal.

Important: By default, only the ToF sensor, Optical Flow sensor, and Neopixel LEDs will be soldered on the module. The brometric sensor and magnetometer footprint is added only for users who wish to build more using the same board. By default these two sensors will not be populated. The colour of the PCB might also be in black or green color depending on the time of purchase, but features and working will reamin the same.

### Note:- Files Related To The Positioning Module Are In The Folder Named "Module"

## Introduction Of ESP32 Drone Bluetooth Speaker Module
<img width="504" height="301" alt="untitled" src="https://github.com/user-attachments/assets/2586178c-27ee-4f6f-a4cc-c513acd9b2ba" />

The ESP32 Drone Bluetooth Speaker Module is a plug-and-play lightweight Bluetooth speaker system to extend the drone's capabilities beyond flight. By adding a simple Bluetooth audio setup, the drone can now deliver real-time announcements, voice messages, or music directly from the air without requiring any additional coding. The entire system works through a standard Bluetooth connection, making it easy to set up, practical for demonstrations, events, and experimental applications while also being fun.

### Note:- Files Related To The Positioning Module Are In The Folder Named "BluetoothModule"

## Introduction Of ESP32 Drone + Positioning Module PCB
<img width="504" height="301" alt="panel" src="https://github.com/user-attachments/assets/09b20204-1465-4589-9c3d-e5b8bc5b3129" />

This PCB Has Both The Drone And Module Combined Into One PCB For Easier Manufacturing And Assembly And This Method Is Faster Than Getting The Both Seperatly

## Add-On Module Template
<img width="504" height="301" alt="untitled" src="https://github.com/user-attachments/assets/c5d3784b-6eb3-4c41-ba14-2ba2f67fd62a" />
<img width="301" height="301" alt="untitled" src="https://github.com/user-attachments/assets/6bef19a3-b832-4a67-b126-ac0b3bf0233c" />

I Have Made A Template Of The Positioning Module For You To Customize, It Is In The Module Folder

-------------------------------------------------------------------------------------------------------------------------------------------------

### As This Project Is Based On LiteWing, The Instructions Are The Same As Litewing Drone Instructions (https://circuitdigest.com/wiki/litewing/)
