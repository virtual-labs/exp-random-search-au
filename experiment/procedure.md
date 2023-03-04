# Procedure
Random search can be used to solve a variety of problems in a graph, including finding the shortest path between two nodes, identifying clusters or communities within the graph, and predicting the likelihood of certain events or outcomes.

## Create the Graph and set the search parameters:
    Select whether directed /undirected graph
    Select creating graph manual/random
    Enter Source Node and Destination Node
    Initiate Search on Graph
## Generate solution:
    Visualize the steps / data structure to store the intermediate values.
    Visualize the path from selecting a starting point on the graph and then following a random path through the graph until the destination is not reached.
    Iterations can be animated; paths can be highlighted.
    The result will be a path which displays the end of the search.

## Evaluate :
    Define following:	
    Time complexity, Space Complexity, Worst scenario, Best scenario
## Algorithm
    Step 1: Select current node x = initial node
    Step 2: Id x = target node , stop with SUCCESS
    Step 3: Expand x, and get a set S of child nodes
    Step 4: Select a node x’ from S at random
    Step 5 : x=x’ and return to Step 2
