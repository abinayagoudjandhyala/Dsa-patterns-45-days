
# Binary Tree & Binary Search Tree – Traversals (Theory Notes)

Today I learned the **core tree traversal techniques** and **Binary Search Tree (BST) fundamentals**.

---

## Binary Tree Traversals

Tree traversals define the **order in which nodes are visited**.

---

### Inorder Traversal (Left → Root → Right)

**Idea:**
Visit left subtree, then root, then right subtree.

**Key Point:**

* In a **BST**, inorder traversal gives **sorted order**.

---

### Preorder Traversal (Root → Left → Right)

**Idea:**
Visit root first, then left subtree, then right subtree.

**Use Case:**

* Useful for copying a tree
* Useful for serialization

---

### Postorder Traversal (Left → Right → Root)

**Idea:**
Visit children before the parent.

**Use Case:**

* Useful for deleting a tree
* Useful when child results are needed before parent (height, depth, diameter)

---

### Level Order Traversal (Level by Level)

**Idea:**
Traverse nodes level by level using a queue.

**Key Point:**

* Uses **BFS (Breadth First Search)**
* Each level is processed separately

---

## Binary Search Tree (BST) Concepts

---

### BST Property

For every node:

```
left subtree values < node value < right subtree values
```

This property applies **recursively** to all nodes.

---

### Important BST Characteristics

* Inorder traversal gives sorted values
* Search, insert, and delete operations are efficient
* BST allows pruning during search

---

## Key Learning

* Traversal choice depends on the problem
* Postorder is important when solving bottom-up problems
* BST structure allows optimized searching
* Understanding traversal order is essential before solving tree problems

---

## Topics Covered Today

* Inorder Traversal
* Preorder Traversal
* Postorder Traversal
* Level Order Traversal
* Binary Search Tree fundamentals

<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/34115769-e660-4419-aa66-5e3fa14fde0f" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/8ebf6672-39ef-4ea8-90fd-02c41f35eafe" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/ad0a68bd-e772-4ccc-8a74-39e0afbebbab" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/b69b6ee5-3949-4610-b3fc-4a2a1ccf0fdf" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/711cfc96-6ea1-4720-82d4-156686ee345e" />


