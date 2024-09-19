# Minuteman-II-Simulation-Project---Python-Implementation
Python simulation of the Minuteman II missile with the Euler method:  
Exercise 1: Missile Overview. 
Exercise 2: Basic calculations. 
Exercise 3: Euler technique using the Coriolis effect. 
Exercise 4: The Euler method with Coriolis, air friction, and centrifugal force. 
Extra: Hypothetical circumstances, such as the Earth not rotating.

## Introduction

This project explores the physics and mathematics behind the trajectory of the Minuteman II ballistic missile. It uses Python code to simulate the missile's flight path, taking into account various forces acting on it.

## Exercises

### Exercise 1: What is Minuteman II?

The Minuteman II is a three-stage solid-fueled intercontinental ballistic missile (ICBM) developed by the United States Air Force. It was in service from 1966 to 2005 and played a crucial role in the US nuclear deterrent strategy during the Cold War.

### Exercise 2: Previous Calculations

This section calculates essential parameters like exhaust velocity, velocity increment, and final velocity for each stage of the missile's flight.

#### 2.a) Exhaust Velocity

Exhaust velocity is calculated using the formula: `u = g * Isp`, where `g` is the acceleration due to gravity and `Isp` is the specific impulse.

#### 2.b) Increment of Velocity

Increment of velocity for each stage is calculated using the Tsiolkovsky rocket equation: `Δv = u * ln(M0/Mf) - (g * tbo)`, where `u` is the exhaust velocity, `M0` is the initial mass, `Mf` is the final mass, `g` is the acceleration due to gravity, and `tbo` is the burn time.

#### 2.c) Final Velocity

Final velocity after each stage is calculated by adding the velocity increment to the initial velocity of that stage.

### Exercise 3: Euler's Method with Coriolis Effect

This exercise simulates the missile's trajectory using Euler's method, considering only the Coriolis effect. It calculates the missile's position, velocity, and acceleration at each time step.

### Exercise 4: Euler's Method with All Forces

This exercise expands on Exercise 3 by including air friction and centrifugal force in the simulation. The code calculates the forces acting on the missile at each time step and updates its position and velocity accordingly.

## Extra Suppositions/Hypotheses

This section explores various "what if" scenarios by modifying parameters in the simulation.

### Earth Not Rotating

This scenario sets the angular velocity of the Earth to zero and analyzes the resulting trajectory.

### Moon's Gravitational Pull

This scenario replaces Earth's parameters with those of the Moon, including its mass, radius, and a null rotation, to simulate the missile's trajectory under the Moon's gravity.

### West-East Launch

This scenario changes the launch angle to 155 degrees, effectively launching the missile westward, and compares the trajectory with the eastward launch.

### Southern Hemisphere Launch

This scenario simulates launching the missile from the southern hemisphere by changing the signs of latitude and longitude, analyzing the impact of the Coriolis effect in the opposite direction.

## Conclusion

This project provides a comprehensive analysis of the Minuteman II missile's trajectory using Euler's method. It explores the impact of various forces on the missile's flight path and provides insights into the physics involved in ballistic missile trajectories.

