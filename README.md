# CPU Scheduling Simulator

A C-based program that simulates common CPU scheduling algorithms used in operating systems. The simulator allows users to enter processes with their burst times and compare different scheduling approaches.

## About the Project

CPU scheduling is an important function of an operating system that determines which process gets access to the CPU.

This project implements three CPU scheduling algorithms:

- First-Come, First-Served (FCFS)
- Shortest Job First (SJF)
- Round Robin (RR)

The program calculates the waiting time and turnaround time for each process, along with the average values.

## Features

- Supports multiple processes
- Implements FCFS scheduling
- Implements non-preemptive SJF scheduling
- Implements Round Robin scheduling with a user-defined time quantum
- Calculates waiting time for each process
- Calculates turnaround time for each process
- Displays average waiting and turnaround times
- Provides a menu-driven interface

## Technologies and Concepts

- C Programming
- Structures
- Arrays
- Operating System Concepts
- CPU Scheduling Algorithms

## Project Structure

```text
CPU-Scheduling-Simulator/
│
├── cpu_scheduler.c
└── README.md
```

## How to Compile

Use GCC to compile the program:

```bash
gcc cpu_scheduler.c -o cpu_scheduler
```

## How to Run

On Windows PowerShell:

```powershell
.\cpu_scheduler
```

## Example Input

You can test the program with four processes:

```text
Number of processes: 4

P1 Burst Time: 5
P2 Burst Time: 3
P3 Burst Time: 8
P4 Burst Time: 2
```

Then select one of the available scheduling algorithms from the menu.

## Scheduling Algorithms

### First-Come, First-Served (FCFS)

Processes are executed in the same order in which they are entered. Once a process starts executing, it runs until completion.

### Shortest Job First (SJF)

The process with the smallest burst time is selected first. This implementation uses a non-preemptive approach.

### Round Robin (RR)

Each process receives CPU time for a fixed period called a **time quantum**. Processes that are not completed during their time quantum wait for their next turn.

## What I Learned

Through this project, I gained practical experience with:

- Implementing CPU scheduling algorithms in C
- Using structures to represent processes
- Calculating waiting and turnaround times
- Comparing different CPU scheduling approaches
- Applying basic operating system concepts

## Author

**KOLIMI HEENA KOUSAR**

GitHub: https://github.com/Heenakousar26
