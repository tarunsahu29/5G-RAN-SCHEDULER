# 5G RAN Scheduling Simulation

## Overview

The 5G RAN Scheduling Simulation project simulates the operation of various scheduling algorithms used in 5G Radio Access Networks (RANs). This simulation provides a comparison of different scheduling strategies for allocating bandwidth to users while considering Quality of Service (QoS) requirements and the fairness of bandwidth distribution. It generates graphical and textual reports for each algorithm's performance, enabling a detailed evaluation of the fairness and efficiency of each approach.

This project includes several scheduling algorithms, such as **Round Robin**, **Shortest Job First (SJF)**, **Priority-based Scheduling**, **Weighted Proportional Fair Scheduling**, **Earliest Deadline First (EDF)**, **Maximal Scheduling with Interference Mitigation**, and **Queue-based Scheduling**. The simulation also computes the fairness of each algorithm based on the variance of allocated bandwidth.

## Features

- **Multiple Scheduling Algorithms**: Supports a variety of scheduling algorithms for allocation of bandwidth, including:
  - **Round Robin Scheduling**
  - **Shortest Job First (SJF)**
  - **Priority-based Scheduling**
  - **Weighted Proportional Fair Scheduling**
  - **Earliest Deadline First (EDF)**
  - **Maximal Scheduling with Interference Mitigation**
  - **Queue-based Scheduling**

- **Fairness Metrics**: Each algorithm's fairness is evaluated based on the variance of the allocated bandwidth, with a lower variance indicating a fairer allocation.

- **Dynamic User Generation**: Users are dynamically generated with random bandwidth requests, QoS types (Low, Medium, High), and priorities.

- **Visual Reports**: Generates graphical plots to visualize:
  - QoS distribution across users.
  - Bandwidth allocation for each scheduling algorithm.

- **Textual Reports**: A detailed text report containing:
  - Summary of each scheduling algorithm's bandwidth allocation.
  - Comparison of scheduling algorithms based on fairness metrics (variance of allocated bandwidth).

- **Output Folder**: All images are saved in the `output/` folder, and a summary text report is saved as `simulation_results.txt`.

## Installation

To get started with this simulation, you'll need Python and the necessary packages. Follow the steps below to install everything required to run the simulation.

### Prerequisites

You need Python 3.7 or higher. The simulation also requires the following Python packages:

- `pandas` - For handling and analyzing data.
- `matplotlib` - For generating graphs and plots.
- `numpy` - For numerical calculations and fairness metric computation.

### Install Dependencies

To install the required packages, you can use `pip`. Run the following command in your terminal:

```bash
pip install pandas matplotlib numpy
