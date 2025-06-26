# Predictive maintenance in automotive: brake pads case
## Introduction
This proof of concept demonstrates how predictive maintenance can be implemented for vehicle fleets in the automotive industry. It helps to enhance vehicle safety and reduce downtime through real-time telemetry, advanced analytics, and machine learning. In this showcase we selected brake pads as vehicle parts to build prediction of their wear based on driving behavior. However, the applied approach and architecture also allow to build prediction for other vehicle maintenance activities, such as tire replacement, fluids checks etc.

We are utilizing [Microsoft Reference Architecture for SDV](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-automotive-connectivity-and-data-solution) and integrating Eclipse Foundation projects, implementing both off-vehicle and in-vehicle components. Our solution leverages technologies based on open standards, such as [COVESA Vehicle Signal Specification (VSS)](https://github.com/COVESA/vehicle_signal_specification), [Eclipse KUKSA](https://github.com/eclipse-kuksa) to seamlessly connect fleet data to the cloud, optimizing the predictive maintenance process across entire fleets.

## Concept
The solution operates as a data-driven pipeline for real-time predictive maintenance. Telemetry data is continuously streamed from vehicles to the cloud, where it is processed, enriched, and used to train a machine learning model that estimates brake pad wear based on driving behavior. Once trained, the model runs inference on incoming data in real time. Both raw telemetry and wear predictions are displayed through a live dashboard, enabling continuous monitoring of vehicle condition.

The following schematic diagram provides a high level overview of the solution.
<img src="images/solution-schematic-diagram.png">

Implementation consists of the following main parts:
- Software/Hardware for simulating real-time data from vehicle sensors
- Software for collecting and processing vehicle data
- ML model for predicting the brake pads wear
- Dashboard showing vehicle live data as well as the brake pads wear prediction

### In a vehicle

TBD

### Off a vehicle

### Dashboard



