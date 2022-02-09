# Design-3A-Temperature-based-Access-Control-project-

## Access control project using RF communication between two MCUs

1. [Summary](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-#summary-of-project)

2. [Youtube Video Demonstration](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-#youtube-video-demonstration-of-the-system)

3. [Code for the Project](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-#the-code-for-the-project-can-be-found-on-these-pages)

4. [System Flowcharts](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/edit/main/README.md#system-flowcharts)

5. [Table showing state changes](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/edit/main/README.md#table-showing-state-changes-during-each-stage-of-the-process)

6. [Circuuit Schematics](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/edit/main/README.md#circuit-schematics)

7. [Simplified RF communication process](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-#simplified-rf-communication-process)

8. [Control System Model](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-#control-system-model)



### Summary of Project: 
<p>This project was an access-controlled system that used temperature as the main restriction parameter to facilitate entry into the workplace while enforcing COVID protocols. It featured wireless communication between two Microcontroller units with one unit controlling servo motors for the physical gates and the other unit controlling the mode of access control and display. A sanitizer station was incorporated into the design using a pump as well as a manual and automatic mode for the system, a PIR sensor was used to detected if the user has based through the gates. A buzzer and Alert system were also used to alert to a user with a higher temperature.</p>

<img src = "https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/final%20flow%20diagram.svg" float="centre" width="1080" />

### Youtube Video Demonstration of the system
[![Watch the video](https://img.youtube.com/vi/kYRVERmXKSE/0.jpg)](https://www.youtube.com/embed/kYRVERmXKSE) 

## The code for the project can be found on these pages:

[Control Centre Arduino MCU Arduino Code](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/Code%20for%20Control%20Centre)

[Gate and Sensor Station MCU Arduino Code](https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/Sensor%20Station%20and%20Gate%20Code)


It was within my responsibilities for the project for the overall design, and functionality of ensuring the system was working together. The wireless communication, software, and synchronisation of the two programs of the system were within my list of responsibilities as well. It was with this project that I was able to develop my skills in C and C++, programming of wireless RF systems, analogue and digital electronics as well as well as glimpse into a deeper understanding of embedded systems when learning to understand how to configure the RF modules.  

## System Flowcharts

### System Flow Chart to show the design process of the Control Centre(Master MCU)
<img src = "https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/control%20centre%20flow%20chart%20.png" float="centre" width="1080" />

## System Flow Chart to show the design process of the Sensor Station(Slave MCU)
<img src = "https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/Blank%20diagram.png" float="centre" width="1080" />

## Table showing state changes during each stage of the process
<img src = "https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/Picture1.png" float="centre" width="1080" />

## Circuit Schematics
### Circuit Schematic of Control Centre 
<img src = "https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/Picture5.png" float="centre" width="1080" />

### Circuit Schematic of Sensor and Gate Station
<img src = "https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/Picture6.png" float="centre" width="1080" />

## Simplified RF communication process
<img src = "https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/Picture3.png" float="centre" width="1080" />

## Control System Model
<img src = "https://github.com/MarkDC95/Design-3A-Temperature-based-Access-Control-project-/blob/main/Picture4.png" float="centre" width="1080" />
