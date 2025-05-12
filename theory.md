### Theory
A random search algorithm works by randomly selecting points from a defined search space and evaluating them to find the best solution to a problem. It explores the space without following a specific pattern, Despite its simplicity, it can be effective in scenarios with large or complex search spaces where exhaustive search is impractical.

<h4>  Algorithm For Random Search</h4>

<ol>
<li><b>Function Input:</b></li>
<ul><li>The 'randomSearch' function takes nodes, links, a start node, and an end node as input.</li></ul>
<li><b>Initialization:</b></li>
<ul><li>Start with an empty path to keep track of the nodes visited during the search.</li></ul>

<li><b>Check Start Node:</b></li>
<ul><li>Verify if the start node has been visited previously..</li></ul>
<ul><li>If it has, backtrack to the previous node and return false.</li></ul>
<li><b>Visit Start Node:</b></li>
<ul><li>Mark the start node as visited and add it to the path.</li></ul>
<li><b>Select Links:</b></li>
<ul><li>Identify all available links from the start node..</li></ul>
<li><b>Random Link Selection:</b></li>
<ul><li>Randomly choose one link from the available links.</li></ul>
<li><b>Check Target Node:</b></li>
<ul><li>Examine if the selected link leads to the end node</li></ul>
<ul><li>If it does, return the path as the solution.</li></ul>
<ul><li>If it doesn't, proceed to the next step.</li></ul>
<li><b>Recursive Call:</b></li>
<ul><li>Call the randomSearch function recursively on the target node.</li></ul>
<li><b>Backtracking:</b></li>
<ul><li>If no path is found from the current node (i.e., the link doesn't lead to the end node), backtrack to the previous node.</li></ul>

<li><b>Repeat:</b></li>
<ul><li>Repeat steps 3-9 until a path is found or all nodes have been explored.</li></ul>
<li><b>No Path Found:</b></li>
<ul><li>If no path is found after exploring all nodes, return false.</li></ul>
