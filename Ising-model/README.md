# Stochastic Simulations with Cellular Automata

The aim of this project was to build stochastic simulations using cellular automata. Previously, I had only worked on deterministic system with a perfectly predictable outcome.
This is a step into new territory where the update steps are probabilistic. 


As an application of this, I chose to experiment with Ising Model and see if I can analyze an Ising system using my simulation.

## Questions
These are the questions I was trying to answer with my simulation.
1. With conditions as follows, try simulating for a few hundred thousand steps for the 2D Ising model, at 5 different temperatures:


   J = 6.34369e-21  # Interaction constant for iron [Joule]


   kB = 1.38065e-23  # Boltzmann constant [Joule / Kelvin]


   h = 0 #No external magnetic field


   size = 32x32

   Plot magnetization against time for these temperatures, and explain which of your trials you think is closest to the critical temperature, and why.

   After this, look at the given critical temperature for the model below. Compare this to your estimates, and describe any differences in behavior at this temperature and your closest estimate.
Critical temperature: T = 1043K
        
2. Using your model with any initial conditions, compare the average magnetization found with one calculated using the Mean Field Theory, from the Eastman (2014).
   Eastman (2014): Eastman, Peter. (2014) Introduction to Statistical Mechanics. 6.7. Retrieved from [https://web.stanford.edu/~peastman/statmech/phasetransitions.html#the-ising-model](https://web.stanford.edu/~peastman/statmech/phasetransitions.html#the-ising-model).
   
   
   Be mindful that the term "H" in this reading is equivalent to what we called "h", and that our "H" is "E".
   If the simulation does not agree, why not? Does this depend on if the simulation is run above, below, or at the critical temperature, or on the magnetic field?
