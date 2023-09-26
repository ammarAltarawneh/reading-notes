# Graphs
**Intro:**
- Graphs are fundamental data structures used in computer science and mathematics.
- They consist of nodes (vertices) and edges that connect these nodes, representing relationships or connections between data points.
- Graphs are versatile and applicable in various domains, including social networks, routing algorithms, and recommendation systems.

**Directed vs Undirected:**
- **Directed Graphs:** Edges have a direction, meaning they go from one node to another. Represented as (u, v) where u is the source node, and v is the destination.
- **Undirected Graphs:** Edges have no direction, and they simply connect nodes without a specific source or destination. Represented as {u, v} or (u, v).

**Complete vs Connected vs Disconnected:**
- **Complete Graphs:** Every pair of distinct nodes is connected by an edge. Often used in combinatorics.
- **Connected Graphs:** There is a path between every pair of nodes in the graph.
- **Disconnected Graphs:** Contains two or more disconnected components or subgraphs, meaning some nodes are isolated from others.

**Acyclic vs Cyclic:**
- **Acyclic Graphs:** Have no cycles, meaning there are no paths that loop back to a node.
- **Cyclic Graphs:** Contain at least one cycle, where you can traverse through nodes and return to the starting point.

**Graph Representation:**
- **Adjacency Matrix:** A 2D array where cell (i, j) represents the presence or absence of an edge between nodes i and j.
- **Adjacency List:** A data structure where each node stores a list of its adjacent nodes, making it efficient for sparse graphs.

**Weighted Graphs:**
- In some graphs, edges have weights or costs associated with them, representing the cost of traversal, distance, or other relevant values.
- Weighted graphs are commonly used in applications like routing, shortest path algorithms, and network analysis.

**Traversals:**
- **Depth-First Search (DFS):** A graph traversal algorithm that explores as far as possible along each branch before backtracking. Uses a stack or recursion.
- **Breadth-First Search (BFS):** A graph traversal algorithm that explores all neighbors of a node before moving to the next level of neighbors. Uses a queue.