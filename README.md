# Simple Signal Generator

This project aims to implement a simple signal generator generating only sine and square waves in C and run on ATmega16. It has 2 parts, the first part is a program to run on a microcontroller called master which gets the 
parameters using a keypad and send them to another microcontroller called slave to generate the wave and display it's parameters on a LCD. A Simulations of using them on ATmega16 in preoteus is available.
This was one of my course projects for Microprocessors.

# Using Instruction

This program has been written in CodeVisionAVR, so simply open PrjM.prj and PrjS.prj using CodeVisionAVR and complie them. Use .hex files to program microcontrollers.

To run the simulation open Simulation.DSN in preoteus, run the simulation and open digital oscilloscope from debug tab. 
Channel B (connected to port C) is the generated signal. You can change it's parameters (Frequency for sine and square, Duty Cycle for Square) and the signal using keypad.