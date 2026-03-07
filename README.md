# Solar-PV-Array
Simulation of a Solar PV system in MATLAB/Simulink to analyze its performance under different  conditions.

Overview: 

This project presents the modeling and simulation of a Solar Photovoltaic (PV) system using MATLAB/Simulink. The system is analyzed under varying environmental conditions such as solar irradiance and temperature. An MPPT algorithm and a DC-DC converter are implemented to maximize power extraction from the PV array.

Objective:
1. To model a solar PV array in MATLAB/Simulink.
2. To analyze I–V and P–V characteristics under different irradiance and temperature conditions.
3. To implement an MPPT algorithm for maximum power extraction.
4. To integrate a DC-DC converter for voltage regulation and improved system efficiency.

System Components:
The main components of the simulated system include:

  PV Array Model: Generates electrical power based on solar irradiance and temperature.

  MPPT Controller: Determines the optimal operating point to extract maximum power.
  
  DC-DC Boost Converter: Adjusts the voltage level and regulates power flow to the load.
  
  Measurement Blocks: Used to monitor voltage, current, and output power.

MPPT Algorithm:

The Maximum Power Point Tracking (MPPT) algorithm is used to ensure that the PV system operates at its maximum power point under changing environmental conditions. The algorithm continuously measures PV voltage and current, calculates power, and adjusts the duty cycle of the converter to track the maximum power point efficiently.

DC-DC Converter Integration:

A boost DC-DC converter is integrated between the PV array and the load. The converter is controlled by the MPPT algorithm to regulate the output voltage and maintain operation at the maximum power point. This improves power extraction efficiency and system performance, especially during rapid changes in irradiance.
