### Theory
##  Algorithm For Random Search

The function "randomSearch" takes as input nodes, links, start node, and end node.
Initialize an empty path.
Check if the startNode has been visited.
a. If visited, backtrack to the previous node and return false.
3.Mark the startNode as visited and add it to the path.
Select all the links available from the startNode.
Choose a random link from the available links.
Check if the target node of the selected link is the endNode.
a. If yes, return the path.
b. If not, call the function recursively on the target node.
If no path is found from the current node, backtrack to the previous node.
Repeat until a path is found or all nodes have been searched.
If no path is found, return false.
