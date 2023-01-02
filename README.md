# CPU-Scheduling-Algorithm-Simulator-in-cpp

A C++ simulator to simulate the behavior of a CPU scheduler, i.e., choosing a process from the ready queue based on a scheduling algorithm to execute it by the processor.

Here there is all of the code for the assignment. More details about he assignment could be found on the pdf names OS+OOP Assignment.pdf
I have also attached a output.pdf for reference and other output files too

This here is a summmary of how this scheduler has been desigend mentioned below

To design a simulator to simulate the behavior of a CPU scheduler in C++, you will need to consider the following steps:

Define the data structures that will be used to represent the processes and the ready queue. You will need to create a class or structure to represent each process, which should include the following information:

Process ID Arrival time Burst time (i.e., the amount of time the process needs to execute) Priority (if using a priority-based scheduling algorithm) Implement the scheduling algorithm that you want to use. This will likely involve creating a function that takes the ready queue as an input and returns the next process to be executed by the CPU. Some common scheduling algorithms include:

First-Come First-Served (FCFS) Shortest Job First (SJF) Priority Scheduling Round Robin (RR) Create a function to simulate the execution of a single process. This function should take a process as an input and update the process's burst time and other relevant information (e.g., waiting time, turnaround time) as the process is executed.

Implement a main function that will simulate the scheduling of multiple processes. This function should initialize the ready queue with the processes to be simulated, and then repeatedly select a process from the ready queue using the scheduling algorithm, execute the process, and update the ready queue as necessary (e.g., by adding new processes or removing completed processes).

Add any additional features or functionality that you want to include in the simulator. This could include the ability to read in process information from a file, display the output of the simulation in a user-friendly format, or allow the user to specify the scheduling algorithm to be used.
