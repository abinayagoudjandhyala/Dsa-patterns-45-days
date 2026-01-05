### Two Pointers – Daily Notes

Today I learned the **Two Pointers technique** and understood when and how to use it.

---

### Core Idea

Two pointers are used to traverse an array from **both ends** instead of using nested loops.
Usually, one pointer starts from the **left** and the other from the **right**.

The pointers are moved based on a **condition** to reduce time complexity.

---

### When to Use Two Pointers

* When the array is **sorted** (or can be sorted)
* When we need to find pairs or combinations that satisfy a condition
* When comparing elements from both ends is helpful

---

### General Approach

* Place one pointer at the **start** (`left`)
* Place one pointer at the **end** (`right`)
* Check the condition using values at both pointers
* Move:

  * `left` pointer forward if we need a bigger value
  * `right` pointer backward if we need a smaller value
* Continue until pointers meet

---

### Problems Solved

**Two Sum II (Sorted Array)**
Used two pointers to find two numbers whose sum matches the target by adjusting pointers based on the sum.

**3Sum**
Fixed one element and used two pointers (`left` and `right`) to find the remaining two elements whose sum equals zero, while avoiding duplicates.

**Container With Most Water**
Used two pointers from both ends to calculate area and moved the pointer with the smaller height to maximize the area.

---

### Why Two Pointers Work

Instead of checking all possible combinations, two pointers intelligently narrow down the search space, reducing time complexity from **O(n²)** to **O(n)** in many cases.

---

### Key Learning

Two pointers help solve problems efficiently by:

* Reducing unnecessary comparisons
* Making decisions based on conditions
* Using array order to our advantage
