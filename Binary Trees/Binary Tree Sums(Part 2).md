
# Binary Tree & BST – Practice Day Notes

Today I solved important problems related to **BST validation, inorder traversal, searching, and lowest common ancestor logic**.

---

## Validate Binary Search Tree (98)

### Core Idea

Check whether a tree satisfies BST property at every node.

### Logic

* Each node value must lie within a valid range (min, max)
* Recursively update boundaries for left and right subtrees

### Key Learning

* Comparing only parent-child is not enough
* Range-based validation is required

---

## Kth Smallest Element in BST (230)

### Core Idea

Use inorder traversal to get nodes in sorted order.

### Logic

* Traverse left → root → right
* Count nodes until reaching k

### Key Learning

* Inorder traversal of BST produces sorted sequence
* Useful for order-statistics problems

---

## Search in a Binary Search Tree (700)

### Core Idea

Use BST property to move left or right.

### Logic

* If target < current → go left
* If target > current → go right
* If equal → return node

### Key Learning

* BST allows efficient pruning
* Time complexity depends on tree height

---

## Lowest Common Ancestor of Binary Tree (236)

### Core Idea

Find the lowest node that has both target nodes in its subtrees.

### Logic

* Traverse left and right recursively
* If both sides return non-null → current node is LCA

### Key Learning

* Works without BST property
* Uses bottom-up recursion

---

## Lowest Common Ancestor of BST (235)

### Core Idea

Use BST ordering to locate split point.

### Logic

* If both nodes are smaller → go left
* If both nodes are larger → go right
* Otherwise → current node is LCA

### Key Learning

* BST LCA is faster than general tree LCA
* Only one subtree is explored

---

## Overall Learning Today

* Strengthened BST fundamentals
* Understood inorder traversal importance
* Learned difference between BST LCA and Binary Tree LCA
* Improved recursive tree reasoning

---

## Problems Solved Today

* 98 — Validate Binary Search Tree
* 230 — Kth Smallest Element in BST
* 700 — Search in a Binary Search Tree
* 236 — Lowest Common Ancestor of Binary Tree
* 235 — Lowest Common Ancestor of BST

<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/4af19948-d4a7-4731-a77d-3b05bba755de" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/b470cfaf-513f-4109-9c23-3611c261aa3a" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/6198bd13-e459-45f5-a8cb-af8bfc0e89d6" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/a1288f9b-e819-4f91-924e-1ab86fc14c97" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/59ebf698-e3c1-49ff-b016-210a393b844d" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/4030c1e0-9112-4e93-b66d-eb64fd28e517" />

