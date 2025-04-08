# Scheduling_Algorithms
Scheduling algorithms are techniques used by operating systems to manage the execution of processes by allocating CPU time efficiently. These algorithms optimize performance metrics like turnaround time, waiting time, and CPU utilization based on specific criteria such as priority, arrival time, or burst time.

# Scheduling Algorithms

A **University Project** showcasing the implementation of various **Operating System Scheduling Algorithms**. This system allows users to easily calculate and visualize the execution of processes using popular scheduling algorithms. It's designed to help students and developers understand the working of process scheduling in operating systems.

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

This project simulates and calculates the **execution of processes** in an operating system using various **scheduling algorithms**. Users can input process details and view how these processes are managed by different algorithms, helping them visualize the scheduling behavior and understand concepts like CPU burst time, waiting time, turnaround time, and response time.

The project provides the following:
- Real-time scheduling process simulations.
- Clear and detailed algorithm execution steps.
- Easy-to-understand output representation.
- Support for multiple OS scheduling algorithms.

## 🚀 Features

- **Supports Multiple Scheduling Algorithms**: Includes **FCFS**, **SJF**, **Round Robin**, **Priority Scheduling**, and others.
- **Easy-to-Use Interface**: Simple, user-friendly UI to input processes and execute scheduling algorithms.
- **Real-Time Calculation**: Automatically calculates key metrics like waiting time, turnaround time, and CPU utilization.
- **Graphical Output**: Visual representation of the scheduling process with Gantt charts.
- **Detailed Execution Steps**: Breaks down the execution of each algorithm to help users understand how processes are scheduled.
- **Cross-Platform Support**: Works across Windows, Linux, and macOS.

## 🛠️ Tech Stack

- **Programming Language**: Python (for algorithm implementation)
- **GUI**: Tkinter (for user interface)
- **Visualization**: Matplotlib (for Gantt chart generation)
- **Algorithms**: FCFS (First Come First Serve), SJF (Shortest Job First), Round Robin, Priority Scheduling, and others

## 📥 Installation

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/SaifKhan2002/Scheduling_Algorithms.git
cd Scheduling_Algorithms
pip install -r requirements.txt
python main.py
