##  Algorithm For Random Search
<ol>
<li>Enter start node and end node</li>
<li>Initialize an empty path</li>
<li>Check if the startNode has been visited
<ul><li>If visited, backtrack to the previous node and return false.</li></ul>
<li>Mark the startNode as visited and add it to the path </li>
<li>Select all the links available from the startNode</li>
<li>Choose a random link from the available links</li>
<li>Check if the target node of the selected link is the endNode
<ul>
    <li>If yes, return the path.</li>
    <li>If not, call the function recursively on the target node.</li>
</ul></li>    
<li>If no path is found from the current node, backtrack to the previous node.
<li>Repeat until a path is found or all nodes have been searched.
<li>If no path is found, return false.
</ol>