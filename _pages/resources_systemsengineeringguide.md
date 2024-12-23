---
layout: archive
title: "Guide - Systems Engineering"
permalink: /resources_systemsengineeringguide/
author_profile: true
---

Systems Engineering Guide

## Engineering Design Phases
### I. Project Definition
- **Define**: Objectives, Requirements, Stakeholder, Budget, Timeline
- **Research**: Existing Technology, Relevant Literature, Emerging Solutions

### II. Design
- **Conceptal Design**: Brainstorm Design Option Space, Identify Multiple Preliminary System Architectures, Feasibility Analysis, Trade-Off Analysis, Concept Selection
- **Engineering Design**: Engineering Calculations, CAD Models, Component Selection, Risk Assessment / Major Challenges
- **Finalized Design**: Bill of Materials, Design Files 

### III. Build
- **Procurement**: Order Materials
- **Fabrication**: Machining, Wiring, Coding
- **Integration**: Integrate Components and Sub Systems

### IV. Test
- **Functionality**: Basic Operation
- **Characterization**: Characterize System Performace, Calibrate Measurements
- **Stress**: Test Requirements Individual, Test Requirements Together, Field Tests

### V. Iterate
- **Rapid Iteration**: Rapidly iterate through steps II-IV to achieve initial prototypes and proof-of-concept designs.
- **Feedback**: Use feedback from inital tests to improve system design.

### VI. Deploy
- **Deploy**: Deploy system for real-world application.
- **Monitor**: Monitor system performance.
- **Document**: Document system design and results, share with community through outlets such as journals / conferences / white papers as appropriate.
		

## Engineering Sub-Systems & Component Examples

### Mechanical
- **Structural**: housings, chassies, backplanes, mounting brackets
- **Fastening and Sealing**: fasteners, clamps, gaskets, o-rings, epoxies
- **Motion Support**: bearings, hinges
	
### Electrical
- **Computing**: computers, microcontrollers, programmable logic controllers (PLCs)
- **Power**: batteries, voltage regulators, electrical switches
- **Sensor Electronics**: analog to digital converters (ADCs), data aquisition (DAQ)
- **Motion Control Electronics**: motor drivers, encoders
- **Interconnects**: circuit boards, wiring harnesses, connectors

### Software
- **Core**: operating system, firmware
- **Scripts**: guidance, navigation, actuator control, sensor control, data handling
- **Algorithms**: PID, Kalman Filters, SLAM, etc.

### Sensors
- **Navigational**: GPS, accelerometer, gyroscope, IMU
- **Optical**: cameras, lidar, bacskatter
- **Acoustic**: sonar, ADCP, DVL, microphone
- **Physical**: temperature, pressure, force
- **Chemical**: conductivity, mass spec, gas analyzers
	
### Motion
- **Actuation, Electrical**: stepper motors, servo motors, DC/AC motors, solenoids
- **Actuation, Hydraulic**: pumps, rotary actuators, cylinders
- **End Effectors, Propulsion**: wheels, propellors, 
- **End Effectors, Manipulation**: robotic arms, grippers, pan-tilt 

## System Requirements
### Basic Requriements
- **SWaP**: Size, Weight, Power
- **Additional**: Operation Duration, Total Lifetime

### Environmental
- **Thermal**: operating temperature range, heat dissipation, insulation
- **Pressure**: atmospheric, submerged environments, vacuum
- **Radiation**: solar, electromagnetic, particle
- **Shock & Vibration**: shock, vibration 
- **Contamination**: corrosive chemical, abrassive particulates, biofouling risks
- **Illumination**: ligthing conditions
- **Terrain**: surface material (rovers), water currents (submersibles), air currents (drones)

### Sensors & Measurments
- **Measurement Basics**: range (min and max values), resolution (bit depth)
- **Measurement Accuracy**: noise (random fluctuations), offset (systematic bias), drift (change over time)
- **Measurement Temporal Factors**: sampling rate, sensor response time, timestamp accuracy and synchronization between data streams
- **Measurement Spatial Factors**: type (point, integrated area, spatial array), spatial range (total area /volume sampled), spatial resolution (minimum area / volume sampled)
- **Interference**: interference between different active sensors

### Electrical
- **Power**: energy capacity, charging rate, voltage regulation, isolation, distribution
- **Communications**: protocols, data throughput
- **Computing**: processing speed, input/outputs, data retention, data redundancy
- **Thermal**: temperature range
- **Electromagnetic Interference**: interference and noise protection

### Mechanical
- **Pressure / Loads**: pressure rating, seals, load rating, vibrational rating
- **Thermal**: temperature range, heat dissipation, insulation
- **Mating / Interfaces**: system connections
- **Stability**: dynamic stability during movements

### Motion
- **Propulsion**: force, speed, acceleration, motion resolution and control
- **Manipulation**: degrees of freedom, resolution, force
- **Navigation**: accuracy, reliability

### Additional
- **Redundancy**: single point failures
- **Reliability & Repair**: ability to fix system issues, lifetime
- **Regulatory**: transportation, safety, environmental
- **Interoperability**: compatability with other systems, electrical and mechanical
- **Scalibility**: replication of system
