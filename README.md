# Embedded_System_Basics

## Overview
This task aims to introduce you to fundamental concepts related to microcontrollers and microprocessors, Arduino board specifications, and essential communication protocols used in embedded systems.

## Task Details

## 1. Microcontrollers vs. Microprocessors
- Research and understand the key differences between microcontrollers and microprocessors.
- Compare their applications, advantages, and limitations.

## 2. Communication Protocols on Arduino
- Research the following communication protocols commonly used in Arduino development:
  - **I2C (Inter-Integrated Circuit)**
  - **UART (Universal Asynchronous Receiver-Transmitter)**
  - **SPI (Serial Peripheral Interface)**
- Understand their working principles, use cases, and how they are implemented on Arduino.

  **Reference Link:**
- [Arduino Communication Protocols](https://docs.arduino.cc/learn/communication/wire/)

## 3. Understanding Arduino Datasheets
- Read and analyze the datasheets of the following Arduino boards:
  - **Arduino Nano**
  - **Arduino Uno**
  - **Arduino Mega**
- Focus on the following aspects:
  - Pin configurations and functionalities(GPIO)
  - Components and specifications(Timer,ADC,etc..)
  
  **Reference Links:**
  - [Arduino Uno Datasheet](https://docs.arduino.cc/hardware/uno-rev3/)
  - [Arduino Nano Datasheet](https://docs.arduino.cc/hardware/nano/)
  - [Arduino Mega Datasheet](https://docs.arduino.cc/hardware/mega-2560/)

## 4. TinkerCad Simulations 
###   Task_1 : Traffic Light Simulation:
   Build a simple traffic light simulation in TinkerCAD using following components :
        
              Arduino UNO
         
              3 LEDs (Red, Yellow, Green

              3 × 220Ω resistors
            
  🎯 Requirements:
         
                🔴 Red ON for 5 seconds
             
                🟡 Yellow ON for 2 seconds
             
                🟢 Green ON for 5 seconds
             
                🔁 Repeat continuously
         
            Only one LED should be ON at any time

###   Task_2 : Reaction Time Tester:

  Build a simple reaction time tester in TinkerCAD using the following components :

        Arduino UNO

        1 LED

        1 Push button

        1 × 220Ω resistor

        1 × 10kΩ resistor (pull-down for button)

  🎯 Requirements:

      Print "Get Ready..." in the Serial Monitor when the simulation starts

      After a random delay (2–5 seconds), turn the LED ON

      Measure and display the reaction time (in milliseconds) when the button is pressed

      If the button is pressed before the LED turns ON, display "Too Early!" and restart the game
         
## Deliverables
- Detailed Report about Micro-controllers v/s Micro-Processors,Communication Protocols
- Working Sketches of TinkerCad Simulation Task
  
## Deadline
- Submit your findings by **[18/02/2025]**.

## Notes
- Ensure you understand the concepts thoroughly, as they form the foundation for embedded systems development.
- Feel free to reach out in case of any doubts or clarifications.

---
Happy Learning! 🚀
