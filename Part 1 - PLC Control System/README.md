# Part 1 - PLC Control System

## Subproject Purpose
Part 1 implements the core PLC control logic for box transfer between conveyors and establishes the project data model.

## Technical Summary
This stage defines the baseline control behavior using TIA Portal, including sensor/actuator coordination, transfer sequencing, and persistent data organization.

## Main Functions Implemented
- `FB_Transferencia (FB1)` for conveyor transfer sequence execution
- `OB1` for cyclic program orchestration
- Data blocks for transfer state and process data (`DB1`, `DB2`)
- PLC tag mapping for I/O and internal variables

## Relevant PLC Logic
- GRAFCET-based transfer sequence
- Transfer between adjacent conveyors
- Position-sensor-driven transitions
- Direction and barrier control in transfer steps
- Box data structure tracking (serial/RFID/type/process flags/occupied cell)

## Technologies Used
- Siemens TIA Portal
- PLC Programming (LADDER)
- Siemens PLC platform

## Role Within the Complete System
Part 1 is the control foundation used by the expansion functions in Part 2 and the communication/supervision integrations in Part 3.
