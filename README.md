# Event-Driven-Simulation
A project that represents a day at a coffee shop
DOCUMENTATION: file:///C:/Users/camer/Desktop/CS150/Project_1/doc/index.html

This project contains an event driven simulation of customers coming into a store.  Data Structures used: Priority Queue, ArrayList, LinkedList, Queue.

The store operates on a 960 minutes word day.  Customers are allowed to join a line (queue) if the line is under 8*n where n is the number of cashiers in the store.
Otherwise, they are sent away as overflow.  After the simulation, appropriate statistics are calculated, such as waiting time and net profit.  The customers follow
a poisson distribution for their arrivals, and the cashiers serve at a rate that follows the same distribution. 

to run on command line: java ExperimentController
