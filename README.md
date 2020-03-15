# fairGhosts — Ant colony controlled ghosts for Ms. Pac-Man


This repository contains the code on which the publication [fairGhosts — Ant colony controlled ghosts for Ms. Pac-Man](https://ieeexplore.ieee.org/document/7744325)
is based. 

The code developed for **fairGhosts** is found in the package `pacman/entries/ghosts/fair`.

### How to run the game
The game can be tested by running the `main method `pacman/Executor`. 

Different run modes of the game can be used depending on configuration of the main method. 

Default setting is:
* **Ghost Controller**: fairGhosts
* **Ms. Pac-Man Controller**: human interaction
* tracing of ghost decision is shown (this means that the planned path of each ghost is visually displayed)
    

## Background
### Ant Colony Optimization
[Ant Colony Optimization [ACO]](https://www.researchgate.net/publication/308953674_Ant_Colony_Optimization) is a metaheuristic inspired by the behaviour of ants foraging for food. 
It can be applied to many different optimization problems than can use an incremental approach to build a solution.

### Ms. PacMan Competition
The game engine used is from the *Ms. Pac-Man vs. Ghost Competition* held during the IEEE World Congress on Computational Intelligence (WCCI 2012). 