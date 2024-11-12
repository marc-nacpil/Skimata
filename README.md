# SKIMATA: Web Application for Visualization of CPU and Memory Management Algorithms

A comprehensive JavaScript-based simulation tool for exploring and understanding key operating system concepts including CPU scheduling algorithms and memory management techniques.

## Overview

JS-Skimata provides interactive simulations for four fundamental operating system algorithms:

1. **Non-Preemptive Priority Scheduling**
   - Process scheduling based on priority levels
   - No interruption once process starts executing
   - Priority queue implementation

2. **Shortest Remaining Time First (SRTF)**
   - Preemptive version of SJF scheduling
   - Dynamic process selection based on remaining burst time
   - Real-time scheduling decisions

3. **First-In-First-Out (FIFO)**
   - Basic queue-based process scheduling
   - Sequential execution of processes
   - Simple implementation of process management

4. **Fixed Partition Memory Management**
   - Static memory partitioning
   - Memory allocation and deallocation
   - Internal and external fragmentation visualization

## Features

- **Interactive User Interface**
  - Real-time visualization of scheduling processes
  - Dynamic Gantt chart generation
  - Process queue visualization
  - Memory partition display
  
- **Simulation Controls**
  - Step-by-step execution
  - Reset capabilities
  
- **Analysis Tools**
  - Average waiting time calculation
  - Average turnaround time computation
  - Memory utilization statistics
  - Fragmentation analysis

## Technical Stack

- **Frontend Framework**: Vanilla JavaScript
- **Styling**: CSS
- **Visualization**: HTML5
