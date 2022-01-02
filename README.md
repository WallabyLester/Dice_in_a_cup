# Dice in a Cup Dynamics From Scratch
**Andru Liu**

## Overview
The goal of this project was to use Lagrangian dynamics to model a complex system. The system in this project is a 6 DOF system of a dice inside of a cup; much like many common playing games with dice being shaken inside of a cup. The cup in this instance is rotating in order to show multiple impacts occurring.

![dice in cup](/images/dice_in_cup.gif "dice_in_cup.gif")

## Usage Instructions
`final_project.ipynb` contains the full simulation code in a jupyter notebook. The animation must be run through a browser. 

## Configuration Instructions
There are two forms of configurations available:
1. The external forces in the F matrix. These cover the force in x, y, and theta of the cup and x, y, and theta of the dice.

2. The initial conditions of the system in the s0 array. This array encompasses the x, y, and theta starting positions of the cup and dice in the first six elements, respectively. The second set of six elements covers the linear velocity in the x and y and angular velocity, w, for the cup and dice. 