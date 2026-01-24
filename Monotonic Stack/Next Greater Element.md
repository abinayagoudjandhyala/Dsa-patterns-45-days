
### Monotonic Stack – Next Greater Element (Day Notes)

Today I solved **LeetCode 496 – Next Greater Element I** using the **monotonic stack pattern**.

---

### Core Idea

Use a stack that maintains elements in **decreasing order** so that the top of the stack always represents the **next greater element** on the right side.

---

### Problem Logic

The goal is to find the next greater element for values in `nums1` by first processing `nums2`.

---

### Approach

* Traverse `nums2` from **right to left**
* Remove all elements from the stack that are **smaller or equal** to the current value
* The stack top gives the **next greater element**
* If the stack is empty, the answer is `-1`
* Store results in a map for fast lookup
* Build the final answer array using values from `nums1`

---

### Why Monotonic Stack Works

* Keeps only useful elements
* Removes unnecessary smaller values
* Ensures constant time lookup for next greater element
* Processes each element only once

---

### Key Learning

* Always check stack empty condition before accessing top
* Right-to-left traversal is important for next greater problems
* HashMap helps connect preprocessed results with required output

---

### Problem Solved

* 496. Next Greater Element I

