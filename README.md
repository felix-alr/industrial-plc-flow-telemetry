# Industrial PLC Flow Telemetry
![PLCnext](https://img.shields.io/badge/PLCnext-Engineer-009639)
![Language](https://img.shields.io/badge/IEC%2061131--3-Structured%20Text-blue)
![Application](https://img.shields.io/badge/Application-Flow%20Telemetry-orange)
![TU Dresden](https://img.shields.io/badge/TU_Dresden-blue)

## Overview
This project consists of a PLCnext project containing the PLC application logic, hardware configuration, and runtime settings for the PLC Flow Telemetry System.

## Key Features
The main features of the PLC Flow Telemetry System are the following.
1. temperature, pressure, and flow velocity are measured for each flow path.
2. the state is determined for each flow path based on minimum and maximum allowable values for each measurement.
3. one inflow and one outflow valve are actuated based on the current state of the system.