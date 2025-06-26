# Predictive maintenance in automotive: brake pads case​
## Introduction
This is a proof of concept that demonstrates how predictive maintenance can be implemented for vehicles’ fleets in automotive. It helps to enhance vehicles safety and reduce downtime through real-time telemetry, advanced analytics, and machine learning. In this showcase we selected brake pads as vehicle parts to build prediction of their wearing depending on a driving behaviour. However, applied approach and architecture allows to build prediction for other vehicle maintenance activities, like tires replacement, fluids checks etc.

We are utilizing [Microsoft Reference Architecture for SDV](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-automotive-connectivity-and-data-solution) as well as integrating Eclipse Foundation’s projects, implementing both off-vehicle and in-vehicle components. Our solution leverages technologies based on open standards such as [COVESA Vehicle Signal Specification (VSS)](https://github.com/COVESA/vehicle_signal_specification), [Eclipse KUKSA](https://github.com/eclipse-kuksa) to seamlessly connect fleet data to cloud, optimizing the predictive maintenance process across entire fleets.​

## Concept

<img src="images/solution-schematic-diagram.png">