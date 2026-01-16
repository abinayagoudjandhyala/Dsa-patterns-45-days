
### Sliding Window – Variable Window Size (Day Notes)

Today I solved **LeetCode 3 – Longest Substring Without Repeating Characters** using the **sliding window (slow–fast pointers)** technique.

---

### Core Idea

Maintain a window that contains **only unique characters**.
Expand the window using a fast pointer and shrink it using a slow pointer whenever a duplicate character appears.

---

### Problem Logic

The goal is to find the **maximum length substring** that does not contain any repeating characters.

---

### Approach

* Use two pointers to represent the current window
* Use a data structure to track characters inside the window
* Move the right pointer to expand the window
* If a duplicate is found, move the left pointer to remove duplicates
* Update the maximum window length

---

### Why Sliding Window Works

* Keeps track of only valid substrings
* Avoids checking all substrings
* Adjusts window dynamically based on conditions
* Runs in linear time

---

### Key Learning

* Variable-size sliding window is useful for substring problems
* Window expands and shrinks based on constraints
* Two pointers help manage dynamic ranges efficiently

---

### Problem Solved

* 3. Longest Substring Without Repeating Characters

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/ab909f94-aefe-4a8e-9fd5-e525630d5413" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/96138417-4785-4175-8e8e-6dd7bce4eb46" />


