

### Sliding Window – Slow & Fast Pointers (Day Notes)

Today I practiced the **sliding window technique** using **slow and fast pointers** to efficiently count valid subarrays.

---

### Core Idea

Sliding window uses two pointers to represent a moving range in the array.
The window expands and shrinks based on given conditions.

---

### LeetCode 795 – Number of Subarrays with Bounded Maximum

**Logic:**

* Move the fast pointer to expand the window
* Track the last position where elements become invalid (greater than the upper bound)
* Track the last position where elements satisfy the condition
* Count valid subarrays ending at each index

---

### Why Sliding Window Works

* Avoids checking all possible subarrays
* Reuses previous window calculations
* Maintains constraints dynamically
* Improves time complexity to linear time

---

### Key Learning

* Slow and fast pointers help manage window boundaries
* Pointer movement depends on constraints
* Sliding window is powerful for subarray and substring problems

---

### Problem Solved

* 795. Number of Subarrays with Bounded Maximum

![WhatsApp Image 2026-01-16 at 1 50 33 PM](https://github.com/user-attachments/assets/8b528510-d93a-4925-8d51-26c42e5b7a42)
![WhatsApp Image 2026-01-16 at 1 50 40 PM](https://github.com/user-attachments/assets/f7033be1-b737-4cc3-b9bf-a814518e0efc)

