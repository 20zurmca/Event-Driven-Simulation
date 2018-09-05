# Event-Driven-Simulation
A project that represents a day at a coffee shop

This project contains an event driven simulation of customers coming into a store.  Data Structures used: Priority Queue, ArrayList, LinkedList, Queue.

The store operates on a 960 minute work day.  Customers are allowed to join a line (queue) if the line is under 8*n, where n is the number of cashiers in the store.
Otherwise, they are sent away as overflow.  After the simulation, appropriate statistics are calculated, such as waiting time and net profit. The simulation is averaged over a user-specified number of simulations.  The customers follow
a poisson distribution for their arrivals (with mean lambda), and the cashiers' service rate follows an exponential distribution specificed by rateOfService. 

to run on command line: java ExperimentController (this class has hardcoded parameters)
alternative: java Launcher (this class expects arguments: int cashierCount, double profitPerCustomer, double costPerCashier, double rateOfService, double customerArrivalRate)

## Demonstration 
<p><b> Launching the program </b></p>
<img src = "https://github.com/20zurmca/Event-Driven-Simulation/blob/master/Demo/CommandLine.PNG" alt = "Command Line Demonstration" />

<p><b> Running the simulation </b></p>
<img src = "https://github.com/20zurmca/Event-Driven-Simulation/blob/master/Demo/Processing.PNG" alt = "running the simulation" />

<p><b> Averaging Results </b></p>
<img src = "https://github.com/20zurmca/Event-Driven-Simulation/blob/master/Demo/AverageResults.PNG" alt = "averaging results" />

