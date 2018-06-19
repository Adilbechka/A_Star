This programm builds a graph from locations.txt and connections.txt files and
then finds a shortest path from one node to the other using A* Algorithm. There 
are two heuristics which are "Straight Line" and "Fewest Links". Straight Line 
heuristic chooses adjasent node to jump to that is closest to destination node.
Fewest Links performs Breadth First Search(BFS) to find path from start to 
destination node.  

To compile: g++ main.cpp


Make sure all files (main.cpp, map.h, node.h, connections.txt, locations.txt) are
in the same folder!

