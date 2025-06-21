# MAZE-SOLVING MECANUM ROBOT
This project was developed using the micro:bit platform. The micro:bit serves as the brain of the robot, handling sensor inputs, motor control, and algorithm execution. The robot uses Mecanum wheels, allowing it to move in any direction (omnidirectional motion), which gives it enhanced maneuverability in confined maze spaces.

### Limitations:
The maze must consist of approximately 90° turns and must not contain disconnected or "floating" walls.

This robot is capable of solving mazes using two algorithms:

### 1) Left-Wall Following

Advantages: —
Limitations: The maze must not contain an "infinite" left wall (e.g., at the edge of the maze), as it would prevent the robot from entering the maze.

### 2) Depth-First Search (DFS)
   
Advantages: The robot can remember the path it took and replay the shortest path back to the start or to the goal.
Disadvantages: It only finds the first possible solution, not necessarily the optimal one.
Limitations: The width of the maze walls must be consistent and not vary significantly.

Example: Solving a Maze Using Depth-First Search

[![Auticko](https://img.youtube.com/vi/PxUHhGyrYmM/0.jpg)](https://www.youtube.com/watch?v=PxUHhGyrYmM)

Example: Repeating the Found Path

[![Auticko](https://img.youtube.com/vi/f8aKKFPSB9Y/0.jpg)](https://www.youtube.com/watch?v=f8aKKFPSB9Y)
