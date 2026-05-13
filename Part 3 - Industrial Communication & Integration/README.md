# Part 3 - Industrial Communication & Integration

## Subproject Purpose
Part 3 integrates industrial communication and supervision layers on top of the automated conveyor, packaging, and labeling process.

## Technical Summary
This stage implements PLC-to-PLC communication, remote I/O exchange, local and external HMI supervision, database registration, and web-based visualization.

## Main Functions Implemented
- PROFIBUS-DP communication between Siemens S7-1500 (master), S7-1200, and ET200L
- KTP600 HMI implementation with WinCC in TIA Portal
- External HMI integration in Citect SCADA via Modbus TCP and `MB_SERVER`
- MySQL registration using `MySQLBridgeClient`
- Siemens web server pages for process monitoring

## Relevant PLC Logic
- Data mapping between S7-1500 and S7-1200 through configured communication addresses
- ET200L signal exchange for remote sensing/actuation
- PLC memory preparation for SCADA variable publishing
- SQL command transfer from PLC application to MySQL server

## Technologies Used
- Siemens TIA Portal
- Siemens S7-1200
- Siemens S7-1500
- ET200L
- PROFIBUS-DP
- WinCC
- KTP600
- Citect SCADA
- Modbus TCP
- MySQL Workbench 8.0
- Siemens Web Server

## Role Within the Complete System
Part 3 adds communication, supervision, and information-system integration to complete the full academic automation solution.
