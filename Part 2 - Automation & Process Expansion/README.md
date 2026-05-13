# Part 2 - Automation & Process Expansion

## Subproject Purpose
Part 2 expands the base conveyor system with routing automation, data-handling functions, and dedicated packaging/labeling logic.

## Technical Summary
This stage restructures and extends the PLC program to support new process requirements, including improved transfer handling and control of routing zones.

## Main Functions Implemented
- Data creation function (`Criar_Dados / FC2`)
- Data transfer function (`Transfer_dados / FC1`)
- Routing-zone control functions (`Control_TD / FB2`, `Control_TE / FB3`, `Control_YZ / FB6`)
- Packaging function block (`FB_Embalamento / FB4`)
- Labeling function block (`FB_Etiquetagem / FB5`)
- Updated transfer function integration (`FB_Transferencia / FB1`)

## Relevant PLC Logic
- Automatic routing priorities for transfers
- Interlocking of transfers through routing conveyors
- Packaging process timing and process flag update
- Labeling process conditions based on box type
- Array-based movement of box records between conveyors

## Technologies Used
- Siemens TIA Portal
- PLC Programming (LADDER)
- Modular OB/FB/FC/DB architecture

## Role Within the Complete System
Part 2 provides the process automation layer that prepares the system for communication, HMI, SCADA, and database integration in Part 3.
