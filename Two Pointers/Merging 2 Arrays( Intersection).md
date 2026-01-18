
### Linked List – Intersection of Two Lists (Day Notes)

Today I solved the **Intersection of Two Linked Lists** problem using the **two-pointer technique**.

---

### Core Idea

Use two pointers, one for each linked list.
Traverse both lists and switch pointers to the other list once they reach the end.

---

### Logic

* Start one pointer at the head of the first list
* Start the other pointer at the head of the second list
* Move both pointers one step at a time
* When a pointer reaches the end, redirect it to the head of the other list
* When both pointers meet, that node is the intersection point

---

### Why It Works

Both pointers travel the **same total distance** by switching lists.
This equalizes the path length and makes them meet at the intersection node.

---

### Key Learning

* No extra memory is needed
* Works in linear time
* Pointer redirection is a powerful linked list trick

---

### Problem Solved

* Intersection of Two Linked Lists

<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/8402d0aa-4011-4ad4-b18a-8f806a1c0439" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/5a096abf-6652-434a-a713-16725fb96544" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/dcac1c2f-b222-4a87-9d89-2d88a12336c6" />
![WhatsApp Image 2026-01-18 at 12 17 59 PM](https://github.com/user-attachments/assets/428e6f3e-5b29-4f07-84aa-69e93a6966a2)

