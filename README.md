# Truck Logistics Route Optimization using A* Search

## Description
This project implements the A* Search algorithm to determine the most efficient route for a truck traveling between locations in the Mahikeng Local Municipality.

The algorithm uses both actual distances and heuristic values (traffic estimates) to find the shortest and most optimal path.

## Problem Statement
The goal is to find the best route from **Disaneng** to **Coligny** while minimizing travel cost.

## Solution Approach
- A graph was created to represent connections between locations
- Distances between locations were defined as weights
- Heuristic values were added based on traffic data
- The A* algorithm was used to compute the optimal route

## Fixes Made
- Completed the graph with all missing nodes and connections
- Added heuristic values for all locations
- Fixed variable naming errors in the given code
- Corrected the goal node to "Coligny"
- Ensured the program runs without errors

## Output
Visited Order:
[Disaneng, Mahikeng, Mmabatho, Slurry, Bakerville, Lichtenburg, Coligny]

Optimal Path:
[Disaneng, Mahikeng, Bakerville, Lichtenburg, Coligny]

Total Cost:
110

## How to Run
1. Open terminal or command prompt
2. Navigate to the project folder
3. Run the following command:
 
