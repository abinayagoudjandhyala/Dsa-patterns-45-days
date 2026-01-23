
### Linked List – Reversal & Swapping (Day Notes)

Today I practiced advanced **linked list pointer manipulation** by solving partial reversal and node swapping problems.

---

### Reverse Linked List II (92)

**Core Idea:**
Reverse only a **specific portion** of the linked list between given positions.

**Logic:**

* Traverse to the node just before the starting position
* Reverse the links of nodes within the given range
* Reconnect the reversed part with the remaining list

**Why It Works:**
By isolating the sublist and reversing it, the rest of the list remains unchanged.

**Key Learning:**

* Partial reversal requires careful reconnection
* Tracking previous and next pointers is crucial

---

### Swap Nodes in Pairs (24)

**Core Idea:**
Swap every two adjacent nodes in the linked list.

**Logic:**

* Process the list in pairs
* Swap pointers between two consecutive nodes
* Move forward to the next pair

**Why It Works:**
Pointer redirection allows swapping without changing node values.

**Key Learning:**

* Dummy nodes simplify head handling
* Pair-wise pointer updates are a reusable pattern

---

### Overall Learning

* Learned controlled pointer manipulation
* Improved understanding of partial reversal and grouped operations
* Strengthened linked list fundamentals

---

### Problems Solved

* 92. Reverse Linked List II
* 24. Swap Nodes in Pairs

![WhatsApp Image 2026-01-23 at 9 07 54 PM](https://github.com/user-attachments/assets/9815b80d-05ba-40fc-b97b-6c13fb0d5a56)
![WhatsApp Image 2026-01-23 at 9 08 08 PM](https://github.com/user-attachments/assets/7f2f3ce1-28f7-47ff-b260-fa69cbd75a3b)
![WhatsApp Image 2026-01-23 at 9 08 21 PM](https://github.com/user-attachments/assets/ca41d917-cd28-4945-b1aa-6f2d7c7c4721)
![WhatsApp Image 2026-01-23 at 9 08 29 PM](https://github.com/user-attachments/assets/c8d301b9-7410-4149-9aea-f71f4b847884)


