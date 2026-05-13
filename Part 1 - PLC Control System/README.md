# Part 1 - PLC Control System

## Purpose
This subproject delivers the foundational PLC control layer of the automation system. It defines the base process logic, data blocks, and execution structure used as the starting point for subsequent expansion and integration phases.

## Technical Description
Part 1 focuses on deterministic machine/process behavior implemented in Siemens PLC logic. The exported blocks show the use of:
- **Main cycle orchestration** through OB1
- **Function blocks (FB)** for transfer-oriented process control
- **Data blocks (DB)** for state and parameter persistence
- **PLC tag mapping** for I/O and internal signal organization

## Contents
- **`Printed codes and databases/`**  
  PDF exports of key PLC program blocks and data definitions.
- **`Report_Part1.pdf`**  
  Formal project documentation for this development stage.
- **`TIA Portal Developed Program.zip`**  
  TIA Portal project archive for the implemented PLC control solution.

## Technologies and Tools Used
- Siemens PLC programming environment
- TIA Portal engineering workflow
- IEC 61131-3 style program organization (OB/FB/DB)
- PDF block printouts for design traceability

## Role in Overall System Architecture
Part 1 implements the **core control foundation**. It is the control baseline upon which Part 2 process expansion and Part 3 communication/integration capabilities are built.
