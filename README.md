# Industrial Automation System with IIoT and Cloud Integration

## Project Overview
This repository contains a multi-stage industrial automation project developed around Siemens PLC engineering and digital integration practices. The system evolves from core PLC control to expanded process automation and industrial communication, then to IIoT-ready integration for supervisory analytics and cloud connectivity.

The project reflects a complete automation lifecycle that combines:
- PLC-based machine and process control
- Engineering development in Siemens TIA Portal
- Industrial communication and data exchange (including OPC UA and MQTT integration patterns)
- IIoT gateway concepts and cloud-connected monitoring workflows
- Academic reporting artifacts and implementation deliverables

Target cloud integration context includes platforms such as AWS, Microsoft Azure, Siemens Insights Hub, and ThingSpeak.

## System Architecture Overview
At a high level, the architecture is organized into three layers:
- **Control layer (PLC programs):** Implements real-time logic, function blocks, data blocks, and process sequencing.
- **Communication and integration layer:** Exchanges operational data between PLCs and higher-level systems through industrial communication mechanisms.
- **IIoT and cloud layer:** Publishes selected plant data for remote monitoring, analytics, and dashboarding in cloud services.

This layered approach separates deterministic control functions from data integration concerns while enabling scalable digitalization.

## Technologies and Engineering Tools
- **Siemens PLC programming** (IEC 61131-3 style blocks and logic)
- **TIA Portal** project development and deployment
- **Industrial communication concepts** (e.g., OPC UA, MQTT)
- **IIoT gateway integration patterns**
- **Cloud connectivity context:** AWS, Azure, Siemens Insights Hub, ThingSpeak
- **Engineering documentation artifacts:** reports, printed code exports, project archives

## Repository Structure
- **`Part 1 - PLC Control System/`**  
  Foundation PLC control implementation, including base logic blocks, data structures, and initial transfer process behavior.
- **`Part 2 - Automation & Process Expansion/`**  
  Extended automation scope with additional control modules, process functions, and packaging/labeling-oriented logic expansion.
- **`Part 3 - Industrial Communication & Integration/`**  
  Communication-focused implementation stage for inter-PLC/integration behavior and higher-level data exchange preparation.

### Subfolder Detail
- **`Part 1 - PLC Control System/Printed codes and databases/`**  
  Exported PDF printouts of core OB/FB/DB blocks and PLC tag definitions for traceable review.
- **`Part 2 - Automation & Process Expansion/Printed code/`**  
  Exported PDF printouts of expanded FB/FC/DB modules used in the second-stage automation design.
- **`Part 3 - Industrial Communication & Integration/Printed codes/`**  
  Exported PDF printouts of communication-related logic for different PLC contexts.

## How the System Works
1. **Base control is implemented in PLC logic** (OB/FB/FC/DB structures) to execute deterministic automation tasks.
2. **Process capability is expanded** through additional control functions and modularized sub-process logic.
3. **Industrial communication interfaces are introduced** to share operational data between automation components.
4. **IIoT gateway and cloud-oriented data flow concepts are applied** to support remote visibility and analytics.
5. **Engineering evidence is documented** through reports, project archives, and printed code exports.

## Demonstration Video
- https://www.youtube.com/watch?v=edk7Aj8i9cU

## Academic and Professional Context
This repository is organized as a Master’s-level engineering portfolio artifact. It is structured to support technical review by academic evaluators, automation professionals, and recruiters assessing industrial control, integration, and IIoT/cloud-readiness competencies.
