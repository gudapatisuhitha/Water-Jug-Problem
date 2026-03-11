🧠 Problem Statement
The Water Jug Problem involves two jugs with fixed capacities and no measurement markings. The objective is to measure an exact amount of water using permitted operations such as filling, emptying, and pouring water between the jugs.

In this project:

Jug 1 capacity = 4 liters
Jug 2 capacity = 3 liters
Target amount = 2 liters
🚀 Approach
The solution uses a state space search approach.

Each state represents the current water levels in both jugs.
The program explores all valid operations:
Fill a jug
Empty a jug
Pour water between jugs
Previously visited states are tracked to prevent repetition and infinite loops.
The search continues until the target amount is obtained.
🧩 Concepts Used
Artificial Intelligence Problem Solving
State Space Representation
Depth-First Search (DFS)
Recursion & Backtracking
Graph Traversal
Cycle Detection (visited states)
🎯 Applications
The Water Jug Problem demonstrates AI search techniques used in:

resource allocation and planning
robotics and automated systems
puzzle solving algorithms
decision-making systems
process optimization and fluid distribution problems
📜 License
This project is open-source and free to use.
