# Introduction to Graphs

Graph theory is a fundamental area of mathematics and computer science that deals with the study of graphs. A graph is a mathematical structure used to represent relationships between objects. It is a versatile and powerful tool with applications in various fields, including computer science, social networks, transportation systems, and more. In this document, we will explore the basics of graphs and various important concepts associated with them.

## 1. What is a Graph?

A **graph** is a mathematical abstraction consisting of two main components: **vertices** (or nodes) and **edges**. Vertices represent objects or entities, while edges represent relationships or connections between these objects. Graphs can be used to model a wide range of scenarios, such as social networks, road maps, computer networks, and more.

### Key Terminology:
- **Vertex (Node):** A fundamental unit of a graph that represents an object or entity.
- **Edge:** A connection between two vertices that represents a relationship or interaction.

Graphs can be classified into various types based on different characteristics. Let's explore some of these classifications:

## 2. Directed vs. Undirected Graphs

### Directed Graph (Digraph):
A **directed graph** is a type of graph in which each edge has a direction associated with it. This means that the edges have a source vertex and a target vertex, and the order in which these vertices are connected matters. In a directed graph, an edge from vertex A to vertex B is different from an edge from vertex B to vertex A.


### Undirected Graph:
An **undirected graph** is a type of graph where edges have no direction. In other words, the connections between vertices are symmetric, and there is no distinction between the source and target vertices.



## 3. Complete vs. Connected vs. Disconnected Graphs

### Complete Graph:
A **complete graph** is a graph in which every pair of distinct vertices is connected by an edge. In a complete graph with 'n' vertices, there are exactly (n * (n-1)) / 2 edges.


### Connected Graph:
A **connected graph** is a graph in which there is a path between any pair of vertices. In other words, every vertex is reachable from every other vertex through a sequence of edges.


### Disconnected Graph:
A **disconnected graph** is a graph that is not connected, meaning there are two or more isolated components within the graph, and there is no path between these components.


## 4. Acyclic vs. Cyclic Graphs

### Acyclic Graph:
An **acyclic graph** is a graph that contains no cycles. A cycle is a sequence of edges that starts and ends at the same vertex, passing through other vertices only once. Acyclic graphs are also called **DAGs** (Directed Acyclic Graphs) when dealing with directed graphs.


### Cyclic Graph:
A **cyclic graph** is a graph that contains one or more cycles. A cycle is a closed path in the graph where you can traverse a sequence of edges and return to the starting vertex.


Understanding these fundamental concepts of graphs is crucial when working with various applications in computer science, network analysis, optimization, and many other fields. Graph theory provides powerful tools to analyze and solve real-world problems by modeling them as graphs and applying graph algorithms.
