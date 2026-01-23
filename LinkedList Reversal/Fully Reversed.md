

### Linked List – Reverse List (Day Notes)

Today I solved the **Reverse Linked List** problem using **pointer manipulation**.

---

### Core Idea

Reverse the direction of links between nodes so that the last node becomes the head of the list.

---

### Logic

* Use three pointers:

  * `prev` to store the previous node
  * `curr` to track the current node
  * `next` to save the next node before breaking the link

* For each node:

  * Store the next node
  * Reverse the current node’s pointer
  * Move pointers forward

* At the end, `prev` becomes the new head.

---

### Why It Works

Each step reverses one link while safely preserving access to the remaining list.
By the end of traversal, all links are reversed.

---

### Key Learning

* Pointer order is very important in linked list operations
* Always save the next node before changing links
* Reversal is a fundamental linked list pattern

---

### Problem Solved

* Reverse Linked List

