# Project 1: Process Scheduler

## Description

This project is part of the CSCE 4600 course at the University of North Texas. Through this project, I'm building a simple process scheduler that takes in a file containing example processes, and outputs a schedule based on the three different schedule types:

- First Come First Serve (FCFS)
- Shortest Job First (SJF)
- SJF Priority
- Round-robin (RR) with Time Quantum equals to 1

Assuming that all processes are CPU bound (they do not block for I/O). The project is written in Golang.

## Steps

1. Clone the repository:

   `git clone https://github.com/Chalieta/CSCE4600_Project1.git`

2. To run using the example processes, type into the command line:
   `go run . example_processes.csv`
