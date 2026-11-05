# Systems of Linear Equations Calculator

## Description

This project is inspired by Math Papa Algebra Calculator and other similar websites that provide a step-by-step solution to math problems. Reviewing examples on websites like these has played a key role in Riley's study routine. We applied the Gaussian elimination algorithm learned in Linear Algebra to implement a system of equations calculator. The calculator shows each step of the matrix operations and back-substitution before providing the solution.

## Technologies

- Python
- NumPy
- Pygame

## Collaborators
**Riley @reddwryly**
- Gaussian Elimination Algorithm
- Back substitution algebra algorithm 

**Braeden @ThatRedBacon**
- UI in Pygame
  - Matrix inputs
  - Reset button
  - Step Display

## Running the Program

### 1.) Install Pygame, Pygame-TextInput, and Numpy

Ensure Python is installed before attempting to continue install

**windows**    
&emsp;copy/paste in the terminal to install:    
  &emsp;&emsp;python -m pip install pygame     
  &emsp;&emsp;python -m pip install pygame-textinput     
  &emsp;&emsp;python -m pip install numpy    

&emsp;copy/paste in the terminal to test pygame, a minigame should run:    
  &emsp;&emsp;python -m pygame.examples.aliens     
    
**Mac**     
&emsp;copy/paste in the terminal to install:     
  &emsp;&emsp;python3 -m pip install pygame     
  &emsp;&emsp;python3 -m pip install pygame-textinput    
  &emsp;&emsp;python3 -m pip install numpy     

&emsp;copy/paste in the terminal to test pygame, a minigame should run:     
  &emsp;&emsp;python3 -m pygame.examples.aliens     

**Troubleshooting**
* If any problems occur with Pygame, please visit the [Pygame GitHub](https://github.com/pygame/pygame) for more information.
* If any problems occur with Numpy, please visit [numpy.org](https://numpy.org/install/) for more information.

### 2.) Run MainUI.py in your IDE or through the terminal

**Windows**    
&emsp;copy/paste in the terminal:   
  &emsp;&emsp;python MainUI.py

**Mac**     
&emsp;copy/paste in the terminal:   
  &emsp;&emsp;python3 MainUI.py

Note: If any issues with the results display occur arithmetic results can also be viewed in the terminal

## Project Status: Completed

Left incomplete: 
- Handling an infinite solution through writing it in parametric form

> Completed:
> * Gaussian Elimination Algorithm
> * Back substitution algebra algorithm
> * Matrix inputs
> * Reset button
> * Step display
