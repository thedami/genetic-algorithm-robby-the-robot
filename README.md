### Robby the Robot Genetic Algorithm

#### Project Overview
This project involves implementing a genetic algorithm to evolve control strategies for Robby the Robot. The goal is to maximize Robby's average cumulative reward as it navigates a grid collecting empty soda cans.

#### Methods
- **Genetic Algorithm:** Utilizes rank selection, single-point crossover, and mutation.
- **Control Strategies:** Represented as 243-character strings, each specifying actions based on Robby's current situation.

#### Key Features
- **Commands:** Includes MoveNorth, MoveSouth, MoveEast, MoveWest, StayPut, PickUpCan, and MoveRandom.
- **Percept Strings:** Encode Robby's surroundings to determine actions.
