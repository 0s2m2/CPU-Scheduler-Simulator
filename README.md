# 🚀 CPU Schedulers Simulator (CS341 - Operating Systems 1)

## 📖 Project Overview
This project simulates various CPU scheduling algorithms to demonstrate the concepts of process scheduling and resource allocation in operating systems. The assignment focuses on analyzing the performance and efficiency of different scheduling approaches.

## 🛠️ Features
- **Non-Preemptive Priority Scheduling:** Includes context switching to manage process execution.
- **Non-Preemptive Shortest Job First (SJF):** Handles the starvation problem if it occurs.
- **Shortest Remaining Time First (SRTF) Scheduling:** Context-switching with starvation handling.
- **FCAI Scheduling Algorithm:** 
  - Adaptive scheduling based on a composite FCAI factor considering priority, arrival time, and remaining burst time.
  - Unique dynamic quantum allocation for process execution.
  - Preemptive and non-preemptive execution phases.

## 📋 Program Requirements
1. **Input:** 
   - Number of processes  
   - Round Robin Time Quantum  
   - Context switching time  
   - Process parameters:
     - Process Name, Color (for graphical representation), Arrival Time, Burst Time, and Priority Number
2. **Output:**  
   - Execution order of processes  
   - Waiting time and turnaround time for each process  
   - Average waiting and turnaround times  
   - Detailed quantum history for FCAI Scheduling  
   - **Bonus:** Graphical representation of process execution  
