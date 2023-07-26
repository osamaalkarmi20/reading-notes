# Trees
A tree is a data structure made up of nodes or vertices and edges without having any cycle. The tree with no nodes is called the null or empty tree.
A tree that is not empty consists of a root node and potentially many levels of additional nodes that form a hierarchy. 

## Traversal Algorithms

### Breadth-First:
It starts at the tree root and explores all of the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level. 
Depth first traversal is where we prioritize going through the depth (height) of the tree first. 
There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root. 
Here are three methods for depth first traversal:
Pre-order: root >> left >> right
In-order: left >> root >> right
Post-order: left >> right >> root
### Depth-First:
It starts at the root node and explores as far as possible along each branch before backtracking.

## Kinds of Trees

### Binary Trees:
A Binary Tree is a data structure composed of nodes where each node has, at most, two children: a left child and a right child. Nodes in a binary tree are connected through edges, forming a hierarchical structure.
The topmost node is called the root, and nodes without children are called leaves. 
Binary Trees are commonly used in various applications, including search algorithms and hierarchical data representation.

### Binary Search Trees (BSTs):
A Binary Search Tree is a specific type of binary tree where the values are stored in a way that allows for efficient searching, insertion, and deletion operations.
The left subtree of a node contains only nodes with values less than the node's value, and the right subtree contains only nodes with values greater than the node's value. 
This property ensures that the tree is always sorted, making it an effective data structure for searching.

### K-ary Trees:
A K-ary Tree is a generalization of a binary tree, where each node can have up to K children instead of just two.
K can be any positive integer, making K-ary trees more flexible in representing hierarchical data.
K-ary trees are used in scenarios where nodes have multiple children, such as in decision trees or representing file systems.
