
### Linked List – Partitioning Using Two Lists (Day Notes)

Today I solved **LeetCode 86 – Partition List** using a **linked list pointer manipulation approach**.

---

### Core Idea

Split the original list into **two separate lists**:

* One list containing nodes with values **less than x**
* Another list containing nodes with values **greater than or equal to x**

After processing all nodes, connect both lists.

---

### Logic

* Traverse the original linked list
* For each node:

  * If value is less than `x`, add it to the left list
  * Otherwise, add it to the right list
* After traversal, connect the left list to the right list
* Set the end of the right list to null to avoid cycles

---

### Why It Works

Separating nodes into two lists maintains the **relative order** of elements while making partitioning simple and efficient.

---

### Key Learning

* Using dummy nodes simplifies list handling
* Pointer manipulation is easier when building new linked lists
* Partitioning problems often use the “build and connect” approach

---

### Problem Solved

* 86. Partition List
![WhatsApp Image 2026-01-20 at 11 19 43 PM](https://github.com/user-attachments/assets/69f08ffc-78e7-4a4d-88b4-10539873b063)
![WhatsApp Image 2026-01-20 at 11 19 51 PM](https://github.com/user-attachments/assets/eada6ff7-615d-4453-b01c-92c3482923e5)

