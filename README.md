# Traffic Light Controller using Verilog

## Overview

This project implements a Traffic Light Controller using Verilog HDL based on a Finite State Machine (FSM). The controller cycles through three traffic light states: RED, GREEN, and YELLOW with predefined timing intervals.

The project was developed and simulated using Xilinx Vivado.

## Features

* Finite State Machine (FSM) based design
* Three traffic light states:

  * RED
  * GREEN
  * YELLOW
* Synchronous state transitions using a clock signal
* Asynchronous reset functionality
* Functional verification using a Verilog testbench

## State Diagram

RED → GREEN → YELLOW → RED

## Timing

| State  | Duration       |
| ------ | -------------- |
| RED    | 5 Clock Cycles |
| GREEN  | 5 Clock Cycles |
| YELLOW | 3 Clock Cycles |

## Project Structure

traffic_light_controller/

├── traffic_light_controller.v

├── traffic_light_controller_tb.v

├── simulation_waveform.png

└── README.md

## Tools Used

* Verilog HDL
* Xilinx Vivado
* Behavioral Simulation

## Learning Outcomes

Through this project, I learned:

* Verilog HDL coding
* Finite State Machine (FSM) design
* Sequential and Combinational Logic
* Testbench development
* RTL simulation and debugging
* Digital Design Fundamentals

## Simulation Result

The controller successfully cycles through:

RED (100) → GREEN (001) → YELLOW (010) → RED (100)

as verified through simulation in Vivado.

## Future Improvements

* Four-way traffic intersection controller
* Vehicle density-based signal control
* Pedestrian crossing support
* FPGA implementation on hardware

## Author

Ameet Kumar Sahoo

B.Tech, Electronics & Telecommunication Engineering

Indira Gandhi Institute of Technology (IGIT), Sarang
