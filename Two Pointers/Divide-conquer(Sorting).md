
### Linked List – Merge Sort Pattern (Day Notes)

Today I solved **LeetCode 148 – Sort List** using the **merge sort technique on linked lists**.

---

### Core Idea

Since random access is not available in linked lists, **merge sort** is the most efficient way to sort them.
It works by dividing the list into smaller parts and merging them in sorted order.

---

### Logic

* Use **slow and fast pointers** to find the middle of the linked list
* Split the list into two halves
* Recursively sort both halves
* Merge the two sorted lists into one sorted list

---

### Why Merge Sort is Used

* Does not require extra array space
* Works efficiently with linked lists
* Maintains stable sorting
* Avoids shifting elements like array sorting

---

### Key Learning

* Slow and fast pointers help find the middle node
* Recursive divide-and-conquer is powerful for linked lists
* Merging two sorted lists is a reusable pattern

---

### Problem Solved

* 148. Sort List
0![WhatsApp Image 2026-01-20 at 11 37 49 PM](https://github.com/user-attachments/assets/ca37170b-fa02-4982-9e77-49f70f504855)
![WhatsApp Image 2026-01-20 at 11 38 05 PM](https://github.com/user-attachments/assets/40d0df63-4f08-4dea-9039-26a37b571578)
