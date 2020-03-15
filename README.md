

This repository contains the code on which the publication [fairGhosts — Ant colony controlled ghosts for Ms. Pac-Man](https://ieeexplore.ieee.org/document/7744325)
is based. 

The game engine used was presented at the IEEE Computational Intelligence and Games Conference 2016.

The code developed for **fairGhosts** is found in the package `pacman/entries/ghosts/fair`.

The game can be tested by running the main method `pacman/Executor`. 
Different run modes of the game can be used depending on configuration of the main method. 
Default setting is:
* Ghost Controller: fairGhosts
* MsPacMan Controller: human interaction
* tracing of ghost decision is shown (this means that the planned path of each ghost is visually displayed)