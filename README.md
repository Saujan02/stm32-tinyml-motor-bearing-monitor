# Working Simulation

This folder documents the simulated motor-bearing health monitoring system.

## Components
- STM32 Nucleo C031C6
- Two potentiometers representing vibration and temperature inputs
- Green LED: Healthy
- Yellow LED: Warning
- Red LED: Fault

## How it works
The firmware reads two analog inputs and applies threshold-based rules to select a health status. The readings and status are printed to the Serial Monitor.

## Current status
The rule-based simulation is working in Wokwi. The trained TinyML model has not yet been successfully deployed to the STM32C031C6 because of firmware memory constraints.
