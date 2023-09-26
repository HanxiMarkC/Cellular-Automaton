**Project Title:** "Exploration of Cellular Automata Simulation"

**Project Date:** Mar 24

**Project Overview:**
- This project focuses on developing a platform for grid-based simulations using cellular automata, a versatile approach with applications spanning arts and sciences.
- Cellular automata provide a powerful tool for experimentation and policy assessment, suitable for exploring complex systems like epidemiology and traffic flow.
- The project aims to create a general framework for visualizing cellular automata, including classic examples such as Conway's Game of Life and Cyclic CA.

**The Algorithm:**
- Cellular automata operate on a 2D grid where each cell has a state, and its next state depends on its current state and the states of its neighbors, governed by specific rules.
- The project explores different rule sets, including those resembling Conway's Game of Life and Cyclic CA, and encourages experimentation with various rules.
- The neighborhood configuration can be customized, such as considering the 8 surrounding cells or extending to include additional neighboring cells.
- The number of states is a flexible parameter that can be adjusted to fit different simulation scenarios.

**Initial State:**
- The simulation requires an initial grid configuration, which significantly influences the simulation's outcomes.
- Two functions are implemented to initialize the grid: one designed to produce interesting results within Conway's Game of Life, and the other generating a grid with states uniformly chosen from the available set of states.

**PyGame Integration:**
- PyGame, a Python game engine, is utilized for animated visualization of 2D cellular automata simulations.
- While the code includes PyGame functions for managing the game window, these details can be mostly disregarded unless an interest in interactive graphics exists.

**Examples:**
1. Demonstrates Conway's Game of Life on a 25x25 grid with an initial state containing non-zero entries in the upper left corner.
2. Shows the same scenario as the previous example but with a random initial state for each cell.
3. Utilizes cyclic rules on a 40x40 grid with a random initialization over 12 states.

## Good Luck!

## Optional resources
Here are some fun examples of cellular automaton application!
- [Simulating COVID-19 with Cellular Automata](https://towardsdatascience.com/simulating-covid-19-with-cellular-automata-aeb820910a9)
- [Zero Player Game](https://www.youtube.com/watch?v=N-BbgqOjIqk)








