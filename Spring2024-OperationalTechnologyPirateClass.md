
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



### Fundamentals of OT Ch 2

### Key Components of OT Systems

- Hardware
  - Sensors: Monitors physical properties like temp/pressure
  - Actuators: Takes instructions from PLC to carry out physical actions such as opening a valve or starting a motor
  - Programable Logic Controllers/PLCs: Processes data from sensors and sends commands to actuators
  - Networking Equipment
 
- Software
  - Operating Systems: Manage the HW resources of a device
  - Applications: Programs that carry out specific tasks
  - Firmware: Low level software that controls a device's hardware
 
### Control Systems

- SCADA: High level control systems to allow for operations monitoring and controlling processes
- Distributed Control Systems: Autonomously manages complex processes across a large facility by distributing control fuctions to various subsystems for increased efficiency and reliability

### Hierarchy

- Enterprise level systems (top)
  - Enterprise Resource Planning to link the operations on the factory floor w/ broader business goals
- SCADA systems (middle)
  - Manages industrial processes
- Middle layers (continued)
  - PLCs or DCs
- Low level: Field devices/sensors

### Modularity 

- Systems uses distinct, independent modules for flexibility, scalability, and efficency in terms of cost effectiveness, but it can increase the attack surface

### Determinism

- If a condition repeats, the same action will result to provide better coordination, predictibility, reliability, and performance but it is less flexible/robust if something unexpected happens or if unplanned changes are made


### Resiliency

- The OTs systems ability to maintain operations/recover quickly from disruptions (i.e. hardware failures or power outages)
- Various stratigies such as isolating problems, implmenting workarounds, and validating different parts of the system exist but it comes at increased cost for redundant hardware, increase overhead complexity, and disaster recovery planning.


### Security

- Focuses on CIA model to prevent unauthorized access and manage risk
- Security can introduce complexity with additional monitoring and updates
- A key element of security is incident response/planning

### Key OT protocols

- Modbus, Profibus, DNP3
  - Meant to provide real time reliable comms and be lightweight w/ little computation power and limited resource usage
  - Modbus: Oldest from 1979 easy deployment/rapid comms
  - Profibus: Greater data capcity and can work w/ a wider range of devices
  - DNP3: Robus and is common in utilities where telemetry and commands need to be handled reliably
