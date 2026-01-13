

### Linked List – Pointer Techniques (Day Notes)

Today I solved multiple **Linked List problems** using **pointer manipulation** and **two-pointer techniques**.

---

### Linked List Cycle (141)

**Logic:**
Use two pointers, slow and fast.
Slow moves one step, fast moves two steps.
If they meet, a cycle exists.

**Key idea:**
Fast pointer will always catch slow pointer inside a cycle.

---

### Linked List Cycle II (142)

**Logic:**
First detect the cycle using slow and fast pointers.
When they meet, move one pointer to the head.
Move both pointers one step at a time.
The node where they meet again is the start of the cycle.

**Key idea:**
Distance relationships in the cycle lead both pointers to the entry point.

---

### Remove Nth Node From End of List (19)

**Logic:**
Find the length of the linked list.
Convert “nth from end” to a position from the start.
Move to the node just before the target node and remove it.

**Key idea:**
To delete a node, access to the previous node is required.

---

### Rotate List (61)

**Logic:**
Find the length of the list and the tail node.
Connect the tail to the head to make the list circular.
Use modulo to reduce unnecessary rotations.
Find the new head position and break the circular link.

**Key idea:**
Treating the list as circular simplifies rotation.

---

### Key Learning

* Slow and fast pointers are powerful for cycle-related problems
* Careful pointer movement is essential in linked lists
* Circular linking helps solve rotation problems efficiently

---

### Problems Solved

* 141. Linked List Cycle
* 142. Linked List Cycle II
* 19. Remove Nth Node From End of List
* 61. Rotate List

![WhatsApp Image 2026-01-13 at 10 42 09 PM](https://github.com/user-attachments/assets/17260329-18bc-43cc-81be-5621e2e542cf)
![WhatsApp Image 2026-01-13 at 10 42 22 PM](https://github.com/user-attachments/assets/52e3b97a-19fc-4733-aec7-67b8850cb822)
![WhatsApp Image 2026-01-13 at 10 42 30 PM](https://github.com/user-attachments/assets/a9d2e522-ac7c-4b3c-864c-dd3fcc980836)
![WhatsApp Image 2026-01-13 at 10 42 46 PM](https://github.com/user-attachments/assets/4ebdf68d-e317-4d52-9b0b-d41d652f0e51)
![WhatsApp Image 2026-01-13 at 10 42 52 PM](https://github.com/user-attachments/assets/4d5d18c1-af06-407f-83c8-29b2011fa3e1)

