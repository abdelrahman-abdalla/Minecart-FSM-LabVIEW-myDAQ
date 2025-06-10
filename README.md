# Minecart Passenger Control – LabVIEW & myDAQ

This project implements a finite state machine (FSM) for a minecart passenger control system using LabVIEW and NI myDAQ.

## Overview
- **Goal:** Simulate and test passenger flow logic for a minecart system  
- **Tools:** LabVIEW 2025, NI myDAQ digital I/O  
- **Role:** Lead developer of FSM logic and subVI architecture  

## Features
- **Reusable SubVIs:** Modular blocks for state transitions and I/O handling  
- **Dual Polling Rates:** 1 Hz loop for system updates and 10 ms loop for responsive input sampling  
- **Functional Globals:** Employed for clean state tracking across subVIs  
- **Reset Logic:** Real-time system reset via a dedicated reset button input  

## Tools & Technologies
- **LabVIEW:** Visual programming and subVI creation  
- **NI myDAQ:** Digital I/O for physical pushbuttons and LEDs  
- **State Machine Design:** Functional global variables, case structures  

## Project Structure


## Author
Abdelrahman Abdalla – [LinkedIn](https://www.linkedin.com/in/abdelrahman-abdalla-)  

---
MIT License © 2025 Abdelrahman Abdalla
