# Systems of Linear Equations Calculator

## Description

This project is inspired by Math Papa Algebra Calculator and other similar websites that provide a step-by-step solution to math problems. Reviewing examples on websites like these has played a key role in Riley's study routine. We applied the Gaussian elimination algorithm learned in Linear Algebra to implement a system of equations calculator. The calculator shows each step of the matrix operations and back-substitution before providing the solution.

### Technologies

- Python
- NumPy
- Pygame

### Collaborators
**Riley @reddwryly**
- Gaussian Elimination Algorithm
- Back substitution algebra algorithm 

**Braeden @ThatRedBacon**
- UI in Pygame
  - Matrix inputs
  - Reset button
  - Step Display

## Running the Program

### 1.) Install Pygame, Pygame-TextInput, and NumPy

Ensure Python is installed before attempting to continue

**windows**    
* Open a PowerShell terminal in the project directory
* Run:    
  - ```python -m pip install pygame```     
  - ```python -m pip install pygame-textinput```     
  - ```python -m pip install numpy```    
* Test Pygame with a minigame. Run:    
  -  ```python -m pygame.examples.aliens```     
    
**Mac**    
* Open a PowerShell terminal in the project directory
* Run:    
  - ```python3 -m pip install pygame```     
  - ```python3 -m pip install pygame-textinput```     
  - ```python3 -m pip install numpy```    
* Test Pygame with a minigame. Run:    
  -  ```python3 -m pygame.examples.aliens```     

**Troubleshooting**
* If any problems occur with Pygame, please visit the [Pygame GitHub](https://github.com/pygame/pygame) for more information.
* If any problems occur with NumPy, please visit [numpy.org](https://numpy.org/install/) for more information.

### 2.) Run MainUI.py in your IDE or through the terminal

**Windows**    
* Open a PowerShell terminal in the project directory
* Run: ```python MainUI.py```    

**Mac**     
* Open a PowerShell terminal in the project directory
* Run: ```python3 MainUI.py```    

Note: If any issues with the results display occur, arithmetic results can also be viewed in the terminal

## Project Status: Completed

Left incomplete: 
- Handling an infinite solution by writing it in parametric form

> Completed:
> * Gaussian Elimination Algorithm
> * Back substitution algebra algorithm
> * Matrix inputs
> * Reset button
> * Step display
