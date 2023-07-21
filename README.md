# Clock with serial communication and buttons
About
=================
In this project a clock was created where the user can adjust hours, minutes, seconds, days, months and years. In addition, the clock has an alarm function, the user can configure the clock both via a serial terminal and also with the help of buttons.

<img src="https://img.shields.io/badge/c-microcontroladores-blue"/> <img src="https://img.shields.io/badge/8%20bits-18f4550-orange"/>

Table of Contents
=================
<!--ts-->
   * [About](#About)
   * [Table of Contents](#table-of-contents)
   * [How to use](#how-to-use)
      * [Prerequisites](#prerequisites)
      * [Button operation](#button-operation)
      * [Serial communication](#serial-communication)
   * [Tests](#tests)
      * [Reading the time and displaying it in the terminal](#reading-the-time-and-displaying-in-the-terminal)
      * [Performing the time editing and displaying it in the first terminal and the LCD](#Performing-the-time-editing-and-displaying-in-the-LCD)
   * [Project status](#project-status)
   * [Technologies](#technologies)
<!--te-->

How to use
=================

Pre Requirements
----
```bash
To run the system you will need to install
*MPLAB X IDE v3.55
*XC8 v1.41
*peripheral-libraries-for-pic18-v2.00rc3
*Proteus Professional 8.5 - SP0
```

Operation of buttons
----
```bash
In this 4-button system
1) Change screen -> being able to follow both Time and Date or alarm
2) Swap cursor -> move the LCD cursor 
3) Increment
4) Decrement
```
serial communication
----
```bash
For the serial communication to work, where the user can update the clock or even show the current data in another terminal, it is necessary to follow the following logic
1) if is typed 1, 1 : The current time will be shown in the second terminal
2) if is typed 1, 2: The current date will be shown in the second terminal
3) if is typed 1, 3: The current alarm will be shown in the second terminal
4) if is typed 2, 1, HH, MM, SS : The clock time will be updated and shown in the second terminal
5) if is typed 2, 2, DD, MM, YY : The clock date will be updated and shown in the second terminal
6) if is typed 2, 3, HH, MM, SS: The clock alarm will be updated and displayed on the second terminalterminal
```

Tests
=================
Reading the time and showing it on the terminal
----
<div align="center">
<img src="https://user-images.githubusercontent.com/43474214/148815770-91bcf66d-ca42-4554-b179-b3fc434b7bba.png" width="700px" />
</div>

Editing the time and displaying it on the LCD
----
<div align="center">
<img src="https://user-images.githubusercontent.com/43474214/148815860-f820d36f-f118-4857-b797-e2e03f519a4c.png" width="700px" />
</div>

project status
=================

<h4 align="center">
🚧 Clock with buttons and serial 🚀 Under construction... 🚧
</h4>

Technologies
=================

<img src="https://img.shields.io/badge/pic-18f4550-orange"/> <img src="https://img.shields.io/badge/IDE-MPLAB-orange"/> <img src="https://img.shields.io/badge/16x2-LCD-orange"/> <img src="https://img.shi elds.io/badge/Compilador-XC8-orange"/> <img src="https://img.shields.io/badge/Linguagem-C-orange"/>

Author
---

Made by Railson Martins 👋🏽.







		
