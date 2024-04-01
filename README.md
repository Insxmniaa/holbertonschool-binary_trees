# C - Binary Trees

## General

1. **What is a binary tree?**
- A tree data structure where every node has two child nodes that form the tree branches.


2. **What is the difference between a binary tree and a binary search tree?**
- A binary tree doesn't follow a specific order and offers flexability.
- A binery search tree arranges nodes so smaller values are on the left and larger ones on right, making searching faster.


3. **What is the possible gain in terms of time complexity compared to linked lists?**
- Lookup is faster for a binary tree than for a linked list because of the way data is organized in these data structures. 
- In a binary tree, each node has at most two children, and the data is organized in a hierarchical manner. This hierarchical structure allows for quicker lookup times as the search can eliminate half of the remaining nodes at each step.
- In a linked list each node only contains a reference to the next node, and the data is organized linearly. This linear structure requires a sequential search through the list to find a specific element.


4. **What are the depth, height, and size of a binary tree?**
- The depth of a node in a binary tree is the total number of edges from the root node to the target node.
- The height of a binary tree is equal to the largest number of edges from the root to the most distant leaf node.
- The size of a tree is the number of nodes.


5. **What are the different traversal methods to go through a binary tree?**
- There are three main traversal techniques: in-order, pre-order, and post-order traversal.


6. **What is a complete, a full, a perfect, a balanced binary tree?**
- Complete Binary Tree: All levels, except possibly the last, are filled, and all nodes are as left as possible.
-  Perfect Binary Tree: All nodes have exactly two children, and all leaf nodes are at the same level.
- Balanced Binary Tree: The heights of any node's left and right subtrees differ by at most one.

---

## Tasks

0. **New node**
- Write a function that creates a binary tree node.


1. **Insert left**
- Write a function that inserts a node as the left-child of another node.


2. **Insert right**
- Write a function that inserts a node as the right-child of another node.


3. **Delete**
- Write a function that deletes an entire binary tree.


4. **Is leaf**
- Write a function that checks if a node is a leaf.


5. **Is root**
- Write a function that checks if a given node is a root.


6. **Pre-oreder traversal**
- Write a function that goes through a binary tree using pre-order traversal.


7. **In-order traversal**
- Write a function that goes through a binary tree using in-order traversal.


8. **Post-order traversal**
- Write a function that goes through a binary tree using post-order traversal.


9. **Height**
- Write a function that measures the height of a binary tree.

 
10. **Depth**
- Write a function that measures the depth of a node in a binary tree.


11. **Size**
- Write a function that measures the size of a binary tree.


12. **Leaves**
- Write a function that counts the leaves in a binary tree.


13. **Nodes**
- Write a function that counts the nodes with at least 1 child in a binary tree.


14. **Balance factor**
- Write a function that measures the balance factor of a binary tree.


15. **Is full**
- Write a function that checks if a binary tree is full.


16. **Is perfect**
- Write a function that checks if a binary tree is perfect.


17. **Sibling**
- Write a function that finds the sibling of a node.


18. **Uncle**
- Write a function that finds the uncle of a node.

---

## Authors
 - Jeannelys 
 - Joel
