
### Two Pointers – Merging Sorted Arrays (Day Notes)

Today I solved multiple problems using the **two-pointer technique** on **sorted arrays**, focusing on merging and comparing elements efficiently.

---

### Core Idea

When two arrays are sorted, use **two pointers** to traverse both arrays at the same time.
At each step, compare elements and move the pointer with the smaller value.

---

### Merge Sorted Array (LeetCode 88)

**Logic:**
Merge two sorted arrays into one sorted array by comparing elements from both arrays and placing the smaller element in the correct position.

**Key idea:**
Two pointers allow merging in linear time without extra comparisons.

---

### Find the Distance Value Between Two Arrays (LeetCode 1385)

**Logic:**
Compare elements from both sorted arrays using two pointers to efficiently check distance conditions and avoid nested loops.

**Key idea:**
Sorted order helps skip unnecessary comparisons.

---

### Heaters (LeetCode 475)

**Logic:**
For each house, use two pointers to find the nearest heater by comparing left and right heater positions.
Track the maximum of all minimum distances.

**Key idea:**
Two pointers help find closest values efficiently.

---

### Why Merging Technique Works

* Uses sorted order to make smart pointer movements
* Avoids unnecessary comparisons
* Reduces time complexity to linear or near-linear

---

### Key Learning

* Two pointers are very powerful with sorted arrays
* Pointer movement depends on value comparison
* Useful for merging, distance calculation, and nearest element problems

---

### Problems Solved

* 88. Merge Sorted Array
* 1385. Find the Distance Value Between Two Arrays
* 475. Heaters

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/837b10cb-ec6f-4d93-9b96-d6becd55c654" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/3c512f26-6964-41bf-bb8b-050ea9e20138" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/282f0fe8-3cc6-4c70-9171-eccba9c245b0" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/22d54224-278a-4e43-8251-4e122f8b4954" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/b0b12c30-d064-47a6-b736-385350316595" />

