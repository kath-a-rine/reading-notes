# Graphs

**What is a graph?**

A non-linear data structure, a collection of vertices(or nodes) potentially connected by edges.

## Terminology

- **Vertex**- A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
- **Edge** - An edge is a connection between two nodes. Is linear.
- **Neighbor** - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
- **Degree** - The degree of a vertex is the number of edges connected to that vertex.
- **Weight** - The number assigned to the edge of a weighted graph.
- **Cycle** -  A node can be traversed and end up back at itself

### Types of Graphs

- **Undirected Graph:** the edge is undirected or bi-directional. Graph does not move in any direction.

- **Directed Graph:** every edge is directed. A node is directed at another node with a required node to be referenced next.

**Complete Graphs:** all nodes are connected to other nodes

**Connected Graphs:** all nodes have at least one edge

**Disconnected Graphs:** some vertices/nodes may not have edges

**Acyclic Graphs:** directed graph without cycles

**Cyclic Graphs:** a graph that has cycles

**Weighted Graphs:**  agraph with numbers assigned to edges

### Graph Representation

**Adjacency Matrix:** represented through a 2 dimensional array

- a sparse graph has few connections
- a dense graph has many connections

**Adjacency List:** a collection of linked lists or array that lists all connected vertices

