# CPU Scheduling Algorithms

This repository contains implementations of various CPU scheduling algorithms in C++. The implemented algorithms include:

- **First Come First Served (FCFS)**
- **Shortest Job First (SJF)**
- **Round Robin (RR)**
- **Shortest Job Remaining First (SJRF)**

## Algorithms Overview

- **First Come First Served (FCFS)**: Processes are executed in the order they arrive, without preemption.
  
- **Shortest Job First (SJF)**: Processes with the shortest burst time are executed first, minimizing average waiting time.
  
- **Round Robin (RR)**: Each process is executed for a fixed time slice (quantum), then moved to the end of the queue.
  
- **Shortest Job Remaining First (SJRF)**: A variation of SJF where the currently executing process can be preempted if a new process with a shorter remaining time arrives.

## Implementation Details

- Each algorithm is implemented using classes and functions in C++. 
- Input parameters include process arrival times and burst timesand quantum size (for RR),with options for manual or random data generation.
- Output includes the sequence of process execution and metrics such as average turnaround time and waiting time.

# Execution Details

## Data Input Options

Decide how to input process data:
- **1. Manually enter data**
- **2. Randomly generate data**

## Setup Instructions

### Step 1: Choose Scheduling Algorithm

Select the scheduling algorithm you want to simulate by entering its corresponding number.

### Step 2: Choose Data Input Method

Choose whether to input data manually or generate it randomly.

### Step 3: Specify Number of Processes

Enter the number of processes you want to simulate.

### Step 4 (Optional for Round Robin): Enter Time Quantum

If you choose Round Robin scheduling, specify the time quantum. Otherwise, enter arrival and burst times for each process.

## Example Usage

1. Choose scheduling algorithm: **3** (for Round Robin)
2. Data input method: **2** (Randomly Generated)
3. Number of processes: **10**
4. Time Quantum (for RR): **4**

Adjust parameters as per your requirements and run the program to simulate CPU scheduling algorithms.

## Implementation Details

- **Language Used**: C++
- **Dependencies**: None
- **How to Run**: Compile the program and run the executable.



