
# Spring 2024 Operational Technology Pirate Class


https://samsclass.info/OT/OT_S24.shtml


### OT vs IT

- OT: Concerned w/ the operation of physical processes (mfg, pwr gen, etc...)
- OT Drives machinering, controlling pressure, valves, temp, etc...
- On the factory/plant floor
- IT: Computers, software, networks and systems for processing/distributing data to support data anlysis, comms, etc..
- IT = office based


### IT/TO is converging

- Integrating the two domains can lead to improved effiency, productivity, and decision making
- IT prioritizes Confidentiality, Integrity, and Availability, whereas OT prioritizes Safety, Reliability, and Productivity

### Network infrastructure for OT

- HW/SW that communicates between OT componments (Sensors, actuators, control systems, etc...)
- Networks may be localized such as LANs or might span whole geographical regions

### Protocols

- Traditional protocols: Modbus, Profibus, DNP3
- Designed for relabiility and real time comms with little regard for security

### Convergence

- TCP/IP is becoming prevalent in OT systems which creates interoperability and data management but introduces more attack surface and exposure


### OT Network architecture

- Enterprise systems > Control Systems > Field Devices
- Consideration factors:
  - Deterministic: Actions occur at set/predictible times
  - Latency: Time between an instruction and action/data transfer
  - Jitter: Variation in latency
 
### Purdue Model

- Not standardized but has dfferent levels for different devices

### Protocols

- Modbus, Profibus, DNP3
  - Meant to provide real time reliable comms and be lightweight w/ little computation power and limited resource usage
  - Modbus: Oldest from 1979 easy deployment/rapid comms
  - Profibus: Greater data capcity and can work w/ a wider range of devices
  - DNP3: Robus and is common in utilities where telemetry and commands need to be handled reliably
 
### OT Network Requirements

- Real time control (determinism), low latency, minimized Jitter

### OT Planning for Contingincies

- OT sytems operate in harsh environments (power plants, factory floor, oil rig)
- Plan aroud equipment failure, electromagnetic interference, environmental conditions
- Need redundancy/backups and hav diveristy in components/technolgies

### OT in Manufacturing

- Automated production processes to improve quality control and production capacity

### OT in Energy/Transportation

- Helps manage generation/distribution of electricity in power plants via monitoring/controling temps, pressure, on/off cycles, etc...

- Controls traffic management flow and signal timings in road traffic, railways, airports, etc...


### OT in Oil and Healthcare

- Oil and Gas OT monitors/controls drilling operations, pipeline flows, leak detection, etc
- Healthcare manages HVAC and devices for patient care
