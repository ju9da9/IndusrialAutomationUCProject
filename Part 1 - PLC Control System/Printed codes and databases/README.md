# Printed Codes and Databases (Part 1)

## Subproject Purpose
This folder provides the printed PLC code and data definitions used to document the Part 1 control baseline.

## Technical Summary
The files are PDF exports of the main PLC blocks and database structures used for conveyor transfer and box tracking.

## Main Functions Implemented
- Main cyclic execution (`Main[OB1].pdf`)
- Transfer function block (`FB_Transferencia (FB1).pdf`)
- Transfer and process data blocks (`Transferencia_DB (DB1).pdf`, `Dados (DB2).pdf`)
- PLC variable mapping (`PLC tags.pdf`)

## Relevant PLC Logic
- Transfer sequence state handling
- Data persistence for conveyor/box status
- Tag-level interface between physical I/O and control logic

## Technologies Used
- Siemens TIA Portal PDF exports
- PLC Programming (LADDER)

## Role Within the Complete System
These files are the reference documentation for the Part 1 implementation that supports all later project stages.
