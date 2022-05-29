# DynamicProgramming
Dynamic Programming - Grid World

Professor Russ Tedrake's Underactuated Robotics course covers dynamic programming and provides an example called grid world. In the grid world, a robot wants to move from its starting position "S" to the end position "E" while avoiding any obstacles/hazards "*" in the environment. I wrote a modified python program where the robot has an additional objective to stay as far away from the hazards as possible. Dynamic programming is useful in such a scenario as it requires an algorithm that can iteratively search the entire grid to find the optimal path. The video on the right shows how the algorithm iteratively identifies the optimal path to the end position and it outputs the minimum distance the robot gets to the hazards.

To run the code, all you need to change is:
- Plot_Updates - Set this flag to 1 for the algorithm to show the grid search in real time. Set it to 0 for the code to run faster and output the computation time.
- grid         - This array contains the grid that the algorithm will recursively search through to find the optimal path. S is the robot's starting position, E is the robot's end position, * represents hazards, and . represents empty spaces.
