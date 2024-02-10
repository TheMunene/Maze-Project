
# Maze project

The repository is a maze project that uses various data structures and algorithms to generate and solve mazes.


### code structure
- README.md: This document serves as the project's documentation, detailing its purpose, usage guidelines, and instructions for contributing.

- main.cpp: Acting as the program's primary entry point, this file initiates program execution. It typically handles variable and object initialization, function/method invocation, and error/exception management.

- maze.h: This file includes both the implementation and header for the Maze class. Utilizing Kruskal's algorithm for minimum spanning trees, the Maze class generates mazes. It offers methods to obtain the maze as a two-dimensional array of cells and to locate the entrance and exit doors.

- traversal.h: Containing the implementation and header for the Traversal class, this file facilitates pathfinding from the maze's entrance to its exit using a depth-first search algorithm. It provides methods for retrieving the path as a two-dimensional array of cells and for verifying if a given position is part of the path.

- image: This directory houses any images or graphics referenced in the documentation.

- executebin: Here, the executable binary resulting from program compilation is stored.
### Data Structures
- Graph data structure: The maze is represented as a graph, where each cell in the maze is a node in the graph and the edges represent the possible paths between the nodes.

- Stack data structure: The depth-first search algorithm used to solve the maze is implemented using a stack data structure.

- Queue data structure: The breadth-first search algorithm used to solve the maze is implemented using a queue data structure.

- Disjoint-set data structure: The Kruskal algorithm (It is used to discover the shortest path between two points in a connected weighted graph.) used to generate a maze is implemented using the disjoint-set data structure.

### Maze Feature
1. Generate new layout "C"
2. Change Object player "P"
3. Change view "V" (2 Dimension, 3 Dimension, Fps)
4. Move the player Up:"W" | Down:"S" | Left:"A" | Right:"D"
5. Rotate maze -YAxis:"J" | -XAxis:"K" | XAxis:"I" | XAxis:"L" (Only In 3dimension)
6. Action For Key --> 1,2,3,4,5
- Key 1 -> Active/Deactive Ambient Light
- Key 2 -> Active/Deactive Diffuse Light
- Key 3 -> Active/Deactive Specular Light
- Key 4 -> Change The Day (Background)
- Key 5 -> Change Wall Transparant or Not
7. Change Maze size , "+" to Increase and "-" to Decrease
8. Arroy Key To Walk Inside Maze While in Fps Mode (ArrowKeyUP , ArrowKeyDOWN , ArrowKeyLEFT, ArrowKeyRIGHT)
9. Change Nim (ID) Rotation Using Mouse Click (Left,Center,Right)
10. Space to Run/Stop another one player.

### Build & Run
**LINUX/UBUNTU**                                         

You Can Use The Codeblock For Linux As Well.
You Can Execute Your Code Using A Text Editor That You Love. Like Atoms, Sublime,Geany Or Another.
Before Executing, You Must Install Some Dependency Of Glut On Linux. What You Need To Do Is (Installation Via Terminal):

Install The Compiler And Necessary Tools.A Fairly Complete Compiler You Can Use G++, How to :
**sudo apt-get install g++ cmake**
Install Freeglut :
**sudo apt-get install freeglut3 freeglut3-dev**
It provides a set of utilities for creating and managing windows, handling input from mouse and keyboard, and creating menus. It is designed to be platform-independent and compatible with multiple programming languages.
Run Using Terminal :
**gcc -o excecutebin main.cpp -lglut -lGL -lm -lGLU -lstdc++**
## Authors
Those who contributed towards this repository;

- [@TheMunene](https://www.github.com/TheMunene)

