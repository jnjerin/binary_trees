
# Binary Trees Overview #
The scripts contained in this repository are implementations and operations of a binary tree, binary search tree, avl tree and binary heap.  

## General ##
What is a binary tree?  
A binary tree is a data structure where each node has at most two children called a left child and a right child.  If a node has only one child, the other child is pointed to NULL.    
If a node doesn't have children, it's called a leaf node.  The nodes are unordered, thus would be slow to search, insert and/or delete.

1. What is the difference between a binary tree and a Binary Search Tree?  
A Binary Search Tree is an abstract data structure called a container that stores data items to memory.  It could also be considered as a type of binary tree.  The left subtree contains only nodes with keys less than the parent.  The right subtree contains only nodes with keys greater than the parent.  The subtrees themselves must also be a binary search tree.  Since the nodes are ordered, the process of searching, inserting and/or deleting would be faster than a binary tree.  

2. What is the possible gain in terms of time complexity compared to linked lists?  
The travel time in a linked list is longer than a binary tree because every node would be visited.  Meanwhile, there are many possible paths to travel in a binary tree.  The lookup time is the best possible gain in implementing a binary tree rather than a linked list.  

3. What are the depth, the height, the size of a binary tree?  
The nodes in a binary tree are connected by a edge.  The sequence formed by a nodes and edges are called a path.  The depth also known as level is the number of edges from the root which starts at 0 to 3.  The height of a node is the number of edges on the longest path between itself and a leaf.  Every node has a height and the root node is 1.  The height of a tree is the number of edges on the longest path between the root and a leaf.  The size of a binary tree is the total number of nodes.  

4. What are the different traversal methods to go through a binary tree?  
Traversal is the process of visiting each node in a binary tree.  There are three traversal methods: In-order Traversal, Pre-order Traversal and Post-order Traversal.  The In-order Traversal method is when the left subtree is visited first, then the root and finally it moves to the right subtree.  The Pre-order Traversal method is when the root node is visited first, then the left subtree and finally the right subtree.  The Post-order Traversal method is when the left subtree is visited first, then the right subtree and finally the root.  

5. What is a complete, a full, a perfect, a balanced binary tree?  
A complete binary tree is when all levels except the last level is filled and all nodes are as left as possible. 
