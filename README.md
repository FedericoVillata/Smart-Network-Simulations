# Smart Network Simulations

Python simulations for queueing models and drone-assisted communication scenarios in smart networks.

## Overview

This repository collects discrete-event simulation scripts developed for academic work on smart networks and performance analysis.

The project includes:
- queueing theory simulations (M/M/1, M/M/2, M/M/m, M/G/1, finite and infinite buffers)
- drone-assisted communication scenarios
- supporting lab reports and project documentation

## Repository Structure

```
├── Queuing model/
│   ├── MM1_infinitebuffer.py
│   ├── MM1_finitebuffer.py
│   ├── MM2_infinitebuffer.py
│   ├── MM2_finitebuffer.py
│   ├── MMm_load.py
│   ├── queueMG1.py
│   └── ...
├── Drone-assisted communication system simulation,/
│   ├── Single Drone in a business scenario.py
│   ├── Drones equipped with PV panel.py
│   ├── Warm-up transient.py
│   └── 2024_MCDSN_lab2.pdf
└── Report on Drone-assisted communication.pdf
```

## Main Features
- event-driven simulations for queueing systems
- configurable arrival and service processes
- delay, queue size, throughput, and load measurements
- drone-assisted offloading scenarios with battery and recharge constraints
- visualization of results through plots

## Requirements
- Python 3.10+
- numpy
- matplotlib
- scipy

## How to Run
python "Queuing model/MM1_infinitebuffer.py"
python "Queuing model/queueMG1.py"
python "Drone-assisted communication system simulation,/Single Drone in a business scenario.py"

## Outputs
Depending on the script, the simulations may provide:

- arrival and departure rates
- average delay
- average number of users in the system
- queue size
- load trends over time
- plots saved locally or displayed with Matplotlib

## Notes
This repository was developed for academic and exploratory simulation purposes.
