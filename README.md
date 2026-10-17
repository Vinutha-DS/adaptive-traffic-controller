# Adaptive Traffic Controller Using Verilog HDL

## 1. Project Overview
This project implements an adaptive traffic controller for two coordinated four-way junctions using Verilog HDL. The design aims to improve traffic flow and support safer road operation.

## 2. Objectives
- Control traffic signals at two junctions.
- Adjust traffic control based on vehicle density.
- Coordinate green signals between junctions using a green-wave controller.
- Support pedestrian requests.
- Provide emergency handling.
- Verify the design using simulation waveforms.

## 3. Tools Used
- Verilog HDL
- Xilinx Vivado
- Simulation waveform analysis

## 4. Main Modules
- `adaptive_traffic_controller.v` — Top-level controller.
- `junction_controller.v` — Traffic signal state machine.
- `vehicle_density.v` — Vehicle density classification.
- `green_wave_controller.v` — Green-wave coordination.
- `generic_timer.v` — Configurable timing support.

## 5. Verification
The design is verified using Verilog testbenches and simulation waveforms to observe traffic signal transitions and controller behavior.

## 6. Project Status
RTL development and simulation are part of the project workflow. Refer to the uploaded source files and simulation evidence for the implemented functionality.

## 7. Author
Electronics and Communication Engineering Student
