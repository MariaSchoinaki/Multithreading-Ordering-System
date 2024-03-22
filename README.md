# Multithreaded Implementation of a Real Time Pizza Restaurant Ordering System

The Real Time Pizza Restaurant Ordering System is a multithreading executable c program that simulates a real time  w pizza restaurant ordering system.
The ordering system is consisted of packers, deliverers and orders. Each of these entities is a thread that sleeps and wakes in the right desired time, which represents the waiting time of a customer in a real world case scenario. In order to lock and unlock an entity (i.e. pizza ovens)  we implemented mutexes to control the access of threads in specific variables correctly.

## How to Run
1. Clone the project.
2. Make sure you have installed a proper c/c++ compiler (Recommended operating system to run this program macOS / Linux).
3. Open your terminal
4. Change the working directory to the cloned projecte's one.
5. Run
   ```sh
   >>gcc PizzaRestaurant.c -o executable 
   >>./executable 10 100  
   ```
6. The simulation has started!


## Features
- Real time processing
- Adaptable ordering system, based on the availability of the restaurant's resources
- Prevents multiple threads from accessing the same shared resource simultaneously with the usage of the mutexes
- Optimized thread structured
- Simulation of the total restaurant stats
- User-Friendly implementation that prints informative messages for each step of the process


## Collaborators
- [Pavlos Fasois](https://github.com/PavlosFas13)
- [Maria Schoinaki](https://github.com/MariaSchoinaki)
- [Christos Stamoulos](https://github.com/ChristosStamoulos)
