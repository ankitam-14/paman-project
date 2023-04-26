This project is for Pacman to find food in a medium sized maze. The importatnt files are as follows:
1. pacman.py - This file is the main file which implemnts the pacman game.
2. searchAgents.py - This file consists of Agents that will be used to seaarch for food in Pacman
3. search.py - This file consists of different algorithms implemented for this project i.e. Astar search and Uniform Cost Search.

Steps to execute the code.
1. This code requires python version 3.6 as some of the libraries do not work in the newer version.
2. Launch the terminal and change the directory to the required folder(AI_Project)
3. To execute the game using Astar strategy:
	python pacman.py -a fn=astar,heuristic=manhattanHeuristic
4. To execute the game using UCS startegy:
	python pacman.py -a fn=ucs

Output
Example Output:
Path found with total cost of 68 in 0.0 seconds
Search nodes expanded: 269
Pacman emerges victorious!
Win Rate:      1/1 (1.00)
Record:        Win

Here 
Search nodes expanded: shows the number of nodes expanded
Win Rate and Record shows whether the Pacman was able to find the food using the algorithm given.