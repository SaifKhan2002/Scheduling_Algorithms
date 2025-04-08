# Scheduling Algorithms

**University Project**:Scheduling algorithms are techniques used by operating systems to manage the execution of processes by allocating CPU time efficiently. These algorithms optimize performance metrics like turnaround time, waiting time, and CPU utilization based on specific criteria such as priority, arrival time, or burst time.A comprehensive simulation of **Operating System Scheduling Algorithms** implemented in Python. This project aims to help students, developers, and enthusiasts understand and visualize the execution of processes using popular scheduling algorithms. It provides an intuitive platform to explore various scheduling techniques used in operating systems.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithms Implemented](#algorithms-implemented)
- [How It Works](#how-it-works)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🖥️ Overview

This project simulates the scheduling of processes in an operating system using several well-known **scheduling algorithms**. It provides a real-time visualization of process execution, helping users understand key metrics such as waiting time, turnaround time, and CPU burst time. Ideal for educational purposes and practical learning, this tool breaks down how various algorithms function under different conditions.

**Key Features:**
- Real-time process scheduling simulations.
- Visual breakdown of the execution process with Gantt charts.
- Clear, step-by-step algorithm execution to foster better understanding.
- Multi-platform support across Windows, macOS, and Linux.

## 🚀 Features

- **Multiple Scheduling Algorithms Supported**: Implements popular algorithms such as:
  - **FCFS (First Come First Serve)**
  - **SJF (Shortest Job First)**
  - **Round Robin (RR)**
  - **Priority Scheduling**
  - **Multilevel Queue (if implemented)**
- **User-Friendly Interface**: A simple, easy-to-use GUI that allows users to quickly input process details and execute scheduling algorithms.
- **Real-Time Calculations**: Automatically computes essential metrics like waiting time, turnaround time, response time, and CPU utilization.
- **Graphical Visualizations**: Displays process execution timelines using Gantt charts, making it easier to understand how scheduling algorithms work.
- **Detailed Execution Flow**: Walks users through each scheduling algorithm with detailed steps to improve comprehension.
- **Cross-Platform Compatibility**: Designed to run on all major operating systems (Windows, macOS, and Linux).

## 🛠️ Tech Stack

The following technologies are used to implement this project:

- **Programming Language**: Python
- **GUI Framework**: Tkinter (for the user interface)
- **Visualization**: Matplotlib (used for generating Gantt charts and graphical outputs)
- **Algorithms Implemented**: 
  - **FCFS (First Come First Serve)**
  - **SJF (Shortest Job First)**
  - **Round Robin**
  - **Priority Scheduling**
  - **Multilevel Queue Scheduling** (if applicable)

## 📥 Installation

To get started with this project, follow the installation instructions below:

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/SaifKhan2002/Scheduling_Algorithms.git
cd Scheduling_Algorithms
pip install -r requirements.txt
python main.py
