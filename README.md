# Digital Logic Project

## Overview of Project
This repository documents a digital logic circuit designed for an Intro to Logic Design course. The circuit was designed and simulated in CircuitVerse, then implemented and debugged on physical hardware using discrete logic ICs. The goal of this project was to translate a theoretical design into a working real-world circuit while validating correct behavior through simulation and hardware testing.

## Circuit Description
The circuit has one pushbutton switch and 2 light-emitting diodes. One LED is labelled "YES",
and the other is labelled "NO". When the switch is pressed and held down, both LEDs are off.
When the switch is released, one of three conditions result in a seemingly random, equally-likely
way: (1) only the YES light is on; (2) only the NO light is on, or (3) the YES and NO lights
alternate being on in a cyclical pattern.

## Design and Simulation
The circuit was first designed and validated in CircuitVerse to ensure correct logical behavior and state transitions prior to hardware implementation.

Concepts demonstrated:
- Combinational logic
- Sequential logic
- State encoding
- Clocked flip-flops
- Next-state logic

CircuitVerse link: [Link to Digital Simulation](https://circuitverse.org/users/290555/projects/ece-265-lab-9-d56acad1-7e8d-4a1e-9048-dd01f5ff1d15)

## Physical Implementation

This circuit was implemented on a breadboard using discrete logic ICs.
The design was first validated in CircuitVerse and then translated to
hardware.

Hardware used
- Solderless breadboard and jumper wires
- 74LS175 (D-Flip Flop), assorted logic IC's, 555 timer
- 1kΩ, 100kΩ resistors for the 555 timer circuit
- 10µF and 0.1 µF capacitors for the 555 timer circuit
- 2 LED's
- 2 1kΩ current-limiting resistors for LEDs

## Hardware Photo
![Physical Implementation](Images/Hardware_Photo.png)


## Simulation Photos

![Main](Images/Main.png)

![Output Logic](Images/Output_Logic.png)

![Steering Logic](Images/Steering_Logic.png)

![State Memory](Images/State_Memory.png)

