# Application of numerical methods on Spring-Mass System

The goal of this project was to apply different numerical approximation techniques focusing on Runga Kutta methods. I chose the spring-mass system
to test out these numerical simulation methods. I implement both the ideal spring-mass system and a dampened spring-mass system.


## Questions

These were the problems I was trying to answer with my simulation.
1. Implement the spring-mass system using RK4 and Euler methods.
2. Write a function to get the order of a numerical method. 
3. Improve the spring-mass system to consider damping effect. Damping coefficient, $\beta$ should be one of the input parameters of the spring-mass class.
   When the damping coefficient is low, the system still oscillates but the amplitude decreases and it comes to rest eventually. It is called an ***underdamped system***. If the coefficient increases, at one point the system comes to rest even without any oscillation, which is called ***critically damped***.
   
   
   3.1 Consider a system with m = 0.25 and k = 30. Using your simulation, **estimate the critical value for the damping coefficient** (i.e. at which value we start to get critically damped from underdamped)
       (Hint: For a given beta, run the simulation several times with different initial position and velocity)
       
       
   3.2 First, keep your mass constant and change the value of spring constant, k. Each time estimate the critical value of the damping coefficient. 
       Then similarly, keep the value of k constant and change the mass of the object and record the critical damping coefficient.  
       Now plot the critical beta vs mass and critical beta vs k that you found. **What is the proportional relationship of critical beta value with mass and spring constant?**
       

## Status

I consider the project complete and am not actively working on it anymore.


## Running the code

The Jupyter notebook was run on a local machine with Python 3.7, I do not expect any errors while running on any other computer.
