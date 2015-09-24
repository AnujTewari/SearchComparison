# SearchComparison
Comparing search algorithms(BFS, DFS and GBFS)
	Navigation is a common problem for intelligent agents (especially robots). The simple 2D version of this problem relates to everything from a robot wandering the hallways of a building, to a taxi navigating the streets of city to get
to a destination.
	We can model navigation as a discrete search by designating way points covering the free space, e.g. laid out on
a grid. The way points (or vertices) are connected by edges which may be safely travelled without causing a collision 
with an obstacle. Thus we can think of the way points abstractly as an undirected graph. The initial state and goal
states are just given as vertices in the graph, and the objective is to find a path that connects them.

The purpose of this project is to implement and compare the performance of 
1. Breadth-first search (BFS), 
2. Depth-First Search (DFS) and 
3. Greedy Best-First Search (GBFS) 
on a navigation problem, i.e. path finding. Here ATM graph(ATMGraph.jpeg) is taken as the navigation model.

The performance and the evalutaion of the three algorithm for the model is shown in PerformanceMetrics.pdf
============================================================================================================================

Language used : Java(JRE 7)

To compile and run the program:
1.   go to AI dir :
2.   under AI dir, do ‘javac *.java’
3.   do ‘java Graph <graph read file path> <start X> <start Y> <goal X> <goalY> <debug mode> <searchType>’

graph read file path : path to read the txt file containing the graph information
start X    	           : x coordinate of start point
start Y    	           : y coordinate of start point
goal X     	           : x coordinate of goal
goal Y     	           : y coordinate of goal
debug mode 	           : 0 if OFF or 1 if ON
searchType 	           : BFS if Breadth First Search
		             DFS if Depth First Search
		             GBFS if Greedy Best First Search	

For e.g : java Graph C:\Anuj\Artificial_Intelligence625\HW1\ATM.graph.txt 10 1 10 20 1 GBFS



