# Drive-Thru Dynamics: A Simulation-Based Analysis of Fast Food Operations

This project involves creating a simulation model of a fast food drive-thru system using **SimPy**, a Python-based discrete-event simulation framework. The simulation analyzes the efficiency of various operational configurations in a drive-thru system, helping identify bottlenecks and optimize service delivery.

## Project Overview

The primary goal of this project is to model and analyze the dynamics of a drive-thru system. Key factors such as **order stations**, **payment stations**, **pickup stations**, and **customer arrival rates** are examined to optimize the overall performance of the system.

The system is simulated over a 120-minute period, and key metrics like **wait times**, **queue lengths**, and **station utilization** are tracked to assess the system's efficiency under different configurations.

## Technologies Used

- **SimPy**: A process-based discrete-event simulation framework for Python.
- **Python**: The core programming language used to build and run the simulation.
- **Matplotlib**: Used for plotting graphs and visualizing data (e.g., wait times and queue lengths).
  
## Features

- **Discrete Event Simulation**: Models the ordering, payment, and pickup stages of the drive-thru.
- **Bottleneck Identification**: Analyzes which station (order, payment, or pickup) is causing the longest wait times.
- **Optimization**: Varying key parameters (e.g., number of stations, customer arrival rates) to find the most efficient configuration.
  
## Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/drive-thru-dynamics.git
