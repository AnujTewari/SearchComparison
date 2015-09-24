# SearchComparison
Comparing search algorithms(BFS, DFS and GBFS)

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



