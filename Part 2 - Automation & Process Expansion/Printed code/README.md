# Printed Code (Part 2)

## Subproject Purpose
This folder documents the PLC implementation used in the Part 2 automation expansion stage.

## Technical Summary
It contains PDF exports of the control, transfer, packaging, labeling, and data-management blocks added or updated in this phase.

## Main Functions Implemented
- `Main (OB1).pdf` – cyclic execution coordination
- `FB_Transferencia(FB1).pdf` – transfer sequence block
- `Control_TD(FB2).pdf`, `Control_TE(FB3).pdf`, `Control_YZ(FB6).pdf` – routing-zone control
- `Transfer_dados(FC1).pdf`, `Criar_Dados (FC2).pdf` – data transfer and data generation
- `FB_Embalamento(FB4).pdf`, `FB_Etiquetagem(FB5).pdf` – packaging and labeling
- `Dados(DB2).pdf` – data structure and process status storage

## Relevant PLC Logic
- Transfer authorization and routing coordination
- Process execution for packaging and labeling
- Data consistency during movement between conveyor arrays

## Technologies Used
- Siemens TIA Portal PDF exports
- PLC Programming (LADDER)

## Role Within the Complete System
These printed files are the technical reference for the Part 2 logic that extends the initial control system with full process automation features.
