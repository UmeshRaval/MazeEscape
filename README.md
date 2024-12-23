# Maze Escape: A 3D procedural generation dungeon game
An innovative 3D maze game that distinguishes itself through procedural generation, providing players with a unique and captivating experience in every playthrough.
Developed on Unreal Engine 5, the game focuses on creating an ever-changing and visually stunning environment. The project's core objectives include delivering a polished and engaging maze escape adventure, ensuring player enjoyment through careful attention to detail, and incorporating customizable parameters for maze complexity and aesthetics.

## Procedural Generation:
The cellular automaton approach for maze generation is a method that treats the maze as a grid of cells, where each cell can be in one of several states (e.g., wall or corridor). The maze evolves through iterations based on simple rules applied to each cell and its neighbors.

Here's a step-by-step explanation of the algorithm:

1.	Initialization

●	Create a grid of cells, initializing all cells as walls.
●	Set initial conditions, such as the starting point, and mark it as a corridor.

2.	Iteration
   
●	For each cell in the grid, apply the following rules:
●	If a cell has fewer than two neighboring corridors, make it a wall.
●	If a cell has two or more neighboring corridors, make it a corridor.
 
4.	Neighborhood Consideration
   
●	Define the neighborhood of a cell, usually considering its immediate orthogonal neighbors. The rules are applied based on the status (wall or corridor) of these neighbors.

6.	Iterative Evolution
   
●	Repeat the iteration process for a specified number of steps or until a certain percentage of the maze has become corridors.
●	The more iterations are performed, the more the maze evolves into a coherent structure.

8.	Randomization

●	Introduce randomness by occasionally flipping the state of cells based on a probability. This adds variety to the maze and prevents it from becoming overly uniform.

## AI Enemy Behavior Tree:

![image](https://github.com/user-attachments/assets/e705f1db-d818-42e8-875d-8b94125baf0b)

## User Interface:

![image](https://github.com/user-attachments/assets/6f53e08a-a929-4674-bc83-2d41ad08f3e9)

## Different Difficulties:

![image](https://github.com/user-attachments/assets/ab90127a-d23e-4726-92ac-3641d51886d6)
![image](https://github.com/user-attachments/assets/213e8f23-869c-49a6-a4e4-712c70db27e5)
![image](https://github.com/user-attachments/assets/f6934f2c-8f63-4298-84e0-e4e0aaaa9b19)


