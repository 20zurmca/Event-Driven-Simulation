# Event-Driven-Simulation
A project that represents a day at a coffee shop

This project contains an event driven simulation of customers coming into a store.  Data Structures used: Priority Queue, ArrayList, LinkedList, Queue.

The store operates on a 960 minute work day.  Customers are allowed to join a line (queue) if the line is under 8*n, where n is the number of cashiers in the store.
Otherwise, they are sent away as overflow.  After the simulation, appropriate statistics are calculated, such as waiting time and net profit. The simulation is averaged over a user-specified number of simulations.  The customers follow
a poisson distribution for their arrivals (with mean lambda), and the cashiers serve at a specified rate. 

to run on command line: java ExperimentController (this class has hardcoded parameters)
alternative: java Launcher (this class expects arguments: int cashierCount, double Profit, double Cost, double rateOfService, double Lamda)

## Demonstration 
<b> Launching the program </b>
<img src = "
