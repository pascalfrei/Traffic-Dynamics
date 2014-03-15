# MATLAB Spring 2014 – Research Plan (Template)
(text between brackets to be removed)

> * Group Name: Pascal/Fabian 
> * Group participants names: Frei Pascal, Stelling Fabian
> * Project Title: Traffic Dynamics

## General Introduction

Understanding traffic dynamics leads to the ability of controlling it. Traffic Systems are very complex systems with a huge number of influences, such as traffic density, reaction time, net distance, velocity and anticipations of the driver. Modelling the problem allows us to estimate the importance of the individual parameters. With this knowledge we know where we can improve traffic systems, which means making a traffic system more efficient and safer.  

## The Model

We investigate a platoon of certain number of cars n, which follow one leading car for a finite period of time. 
The behavior of the leading car, which is described by its velocity gradient, is given. Further parameters are the reaction time T' of the following drivers, the number of anticipated vehicles na, the relavtive distance dr, the relative distance error Vs, the inverse TTC error rc, the velocity and the deceleration.
To simplify the problem we make certain assumptions: 
- every driver has the same reaction time. 
- each car is bound to the same relative distance error and the same inverse TTC error. 



## Fundamental Questions

The fundamental question is how the number of vehicles in the queue, which all have fixed parameters, and the needed reactiontime time are related to each other. 

Additional we will investigate how velocity and reaction time in a modell with a fixed platoon size are related to each other. 




## Expected Results

In generall we expect three different scenarios depending on the mentioned parameters:
- all cars decelerate flawless, which means that the relativ distance remains constant.
- there won't be an accident but the relative distance oscillates.
- accident. 

We expect that a higher number of vehicles in a platoon demands a shorter reaction time, whereas a small amount of vehicles allows a slower reaction time. 

We also expect that a higher velocity requires a shorter reaction time. 

## References 

- Delays, inaccuracies and anticipation in microsopic traffic models, Martin Treiber, Arne Kesting, Dirk Helbing, 21st February 2005
- Possible extension to the above model:
  In the beginning every car has his own individual velocity. Consequently the relative distance between the cars in the   moment of deceleration is variable. 

  Another sensefull extension of the model would be variable reaction times. 
(Explain possible extension to the above models)
(Code / Projects Reports of the previous year)


## Research Methods

(Cellular Automata, Agent-Based Model, Continuous Modeling...) (If you are not sure here: 1. Consult your colleagues, 2. ask the teachers, 3. remember that you can change it afterwards)


## Other

(mention datasets you are going to use)
