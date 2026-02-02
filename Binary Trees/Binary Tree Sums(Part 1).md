
# Binary Tree & BST – Practice Day Notes

Today I solved multiple **core tree problems** covering **BFS, DFS, recursion, diameter logic, and BST pruning**.

---

## Diameter of Binary Tree (543)

### Core Idea

Find the longest path between any two nodes in the tree.

### Logic

* For every node, calculate left height and right height
* Diameter at that node = left height + right height
* Track the maximum value globally

### Key Learning

* Postorder traversal is required
* Height calculation is reused to compute diameter

---

## Range Sum of BST (938)

### Core Idea

Calculate sum of all nodes whose values lie within a given range.

### Logic

* Use BST property to prune branches
* Skip left subtree if value is too small
* Skip right subtree if value is too large

### Key Learning

* BST ordering helps reduce unnecessary traversal
* Optimized DFS traversal

---

## Level Order Traversal (102)

### Core Idea

Traverse the tree **level by level** using BFS.

### Logic

* Use a queue
* Process nodes level-wise using queue size
* Store each level separately

### Key Learning

* BFS is best for level-based problems
* Queue-based traversal pattern

---

## Maximum Depth of Binary Tree (104)

### Core Idea

Find the height of the tree.

### Logic

* Depth = 1 + max(left subtree depth, right subtree depth)
* Use recursion or postorder traversal

### Key Learning

* Height calculation is a base for many tree problems
* Bottom-up DFS approach

---

## Invert Binary Tree (226)

### Core Idea

Swap left and right children of every node.

### Logic

* Recursively invert left and right subtrees
* Swap pointers at each node

### Key Learning

* Simple recursion pattern
* Helps understand tree structure manipulation

---

## Overall Learning Today

* Practiced both BFS and DFS traversal patterns
* Understood bottom-up tree recursion
* Applied BST property for optimized searching
* Strengthened tree traversal fundamentals

---

## Problems Solved Today

* 543 — Diameter of Binary Tree
* 938 — Range Sum of BST
* 102 — Binary Tree Level Order Traversal
* 104 — Maximum Depth of Binary Tree
* 226 — Invert Binary Tree

<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/5ac5d970-cdae-469f-9278-991058dad4a3" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/07346318-f1f4-4dc9-b2b7-cc598925fd5d" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/52290976-25f5-4957-aea4-8f4114df935d" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/a79fe880-597a-423c-9dfd-368c81083fb3" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/37a2ea56-95e4-41c4-a3d5-20f3e8aecd4c" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/24e1007b-002e-4a79-a44d-c48975806b51" />


