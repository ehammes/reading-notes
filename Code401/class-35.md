# Read: 35 - Graphs

## Reading

[Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

### Notes

- A **graph** is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.
- Terminology:
  - **Vertex** - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
  - **Edge** - An edge is a connection between two nodes.
  - **Neighbor** - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
  - **Degree** - The degree of a vertex is the number of edges connected to that vertex.
- **Undirected Graph** is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.
- **Directed Graph** also called a Digraph is a graph where every edge is directed. Unlike an undirected graph, a Digraph has direction. Each node is directed at another node with a specific requirement of what node should be referenced next.
- **Complete graph** is when all nodes are connected to all other nodes.
- **Connected graph** is graph that has all of vertices/nodes have at least one edge.
- **Disconnected graph** is a graph where some vertices may not have edges.
- **Acyclic graph** is a directed graph without cycles.
- **Cyclic graph** is a graph that has cycles.
- **Adjacency list** is a collection of linked lists or array that lists all of the other vertices that are connected. An adjacency list is the most common way to represent graphs.
- Traversals through graphs: The traversals itself are like those of trees. Here is what the algorithm
  - `Enqueue` the declared start node into the Queue.
  - Create a loop that will run while the node still has nodes present.
  - `Dequeue` the first node from the queue
  - If the `Dequeue‘d` node has unvisited child nodes, add the unvisited children to visited set and insert them into the queue.
- **Weighted graph** is a graph with numbers assigned to its edges. These numbers are called weights. This is what a weighted graph looks like:
- Real world examples of graph uses: GPS and Mapping, Driving Directions, Social Networks, Airline Traffic, Netflix uses graphs for suggestions of products
