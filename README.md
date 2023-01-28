# Suspension-Bridge-Using-Diffrential-Equations
This code is a simulation of a simple harmonic oscillator using the numerical integration method called odeint. The simple harmonic oscillator is a physical system that oscillates about an equilibrium position with a restoring force proportional to the displacement from the equilibrium position. The model of the system is described by a second-order ordinary differential equation, which is the equation of motion of the system.

The first part of the code defines some parameters of the model, such as the mass of the roadway, the damping coefficient, and the spring constant. These parameters are used to define the behavior of the system.

The second part of the code defines the initial conditions of the system, such as the initial displacement and velocity.

The third part of the code defines the time range for the simulation and the time step, this time range will be used to plot the displacement over time.

The fourth part of the code defines a function called model() which takes two inputs x and t .The function model is using the inputs to solve the system of differential equations using the odeint function and this is done by updating the displacement and velocity based on the equation of motion.

The fifth part of the code defines a function called F(t) which represents the external force acting on the system. In this example, the external force is a simple sinusoidal function of time with amplitude A and frequency omega.

The sixth part of the code uses the odeint() function to solve the system of differential equations for the given time range, initial conditions and the external force.

Finally, the seventh part of the code uses the matplotlib.pyplot library to plot the displacement of the system over time.
The output of the code is a graph of the displacement of the system over time, which shows how the displacement of the system changes as a function of time in response to the external force.
