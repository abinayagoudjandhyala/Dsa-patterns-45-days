
# Binary Search – Modified Patterns (Day Notes)

Today I solved multiple problems based on **modified binary search**, where standard binary search logic is adapted to handle rotations, boundaries, and 2D grids.

---

## Search in Rotated Sorted Array (33)

### Core Idea

Use binary search to identify which half of the array is sorted and decide where the target lies.

### Key Learning

* One side is always sorted in rotated arrays
* Compare target with sorted half boundaries

---

## Find Minimum in Rotated Sorted Array (153)

### Core Idea

Use binary search to locate the rotation point, which is the **minimum element**.

### Key Learning

* Compare mid element with right boundary
* Minimum lies in the unsorted half

---

## Search Insert Position (35)

### Core Idea

Find the correct index where the target exists or should be inserted.

### Key Learning

* Binary search can return position even if element is not present
* Boundary handling is important

---

## First and Last Position of Element in Sorted Array (34)

### Core Idea

Use binary search twice to find **leftmost and rightmost occurrences** of the target.

### Key Learning

* Modify binary search to move toward boundaries
* Useful for handling duplicates

---

## Search a 2D Matrix II (240)

### Core Idea

Start from top-right or bottom-left and eliminate one row or column at each step.

### Key Learning

* Matrix sorted properties help reduce search space
* Works similar to binary search logic

---

## Overall Learning

* Modified binary search handles special constraints
* Rotation and boundary problems need careful comparisons
* Binary search can be applied beyond simple arrays

---

## Problems Solved Today

* 33 — Search in Rotated Sorted Array
* 153 — Find Minimum in Rotated Sorted Array
* 35 — Search Insert Position
* 34 — First and Last Position of Element in Sorted Array
* 240 — Search a 2D Matrix II

<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/4c2c026b-985f-432e-b099-257a6e1e6c8a" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/fa0cd488-3f8d-4a26-852e-206a075b3852" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/572ab124-d21c-41a0-a19c-896fce255e37" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/92c82331-8580-4c94-94c1-5aea75402c67" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/308815c6-1b49-49a3-bd15-ddc1f553d414" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/01610465-9269-40ad-ba33-6df1e8f539e9" />

