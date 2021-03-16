# MazeGrid
Application of on-policy first-visit Monte Carlo Control and Q-learning to a modified version of GridWorld. In this problem, the agent starts randomly at one of the four corners of the grid, and must find the chest in the middle. There are four barriers that force the agent to either one of two paths leading to the most rewarding terminal state in the center. Additionally, there are two fixed bombs that act as terminal states and return a large negative reward. In total, there are three terminal states. Collisions with barriers have no effect. 

I provided code to implement GridMaze with a nine-by-nine grid and when run it'll be imediately evident that Q-learning is far much faster in comparison to MonteCarlo. 


**** The approproate file to run is Cogs182FinalProject.ipynb
