
### Interval Pattern – Merge Overlapping Intervals (Day Notes)

Today I solved **LeetCode 56 – Merge Intervals** using the **overlapping interval merging pattern**.

---

### Core Idea

Overlapping intervals can be merged by **sorting them by start time** and comparing each interval with the previously merged one.

---

### Logic

* Sort all intervals based on starting value
* Initialize the first interval as the current merged interval
* Traverse remaining intervals:

  * If the current interval overlaps with the previous one, extend the end value
  * If there is no overlap, start a new merged interval
* Store merged intervals in the result list

---

### Overlap Condition

Two intervals overlap when:

```
current.start ≤ previous.end
```

---

### Why This Works

Sorting ensures intervals are processed in order.
Merging adjacent overlapping ranges avoids duplicates and unnecessary intervals.

---

### Key Learning

* Sorting is required before merging
* Boundary conditions are important for correct overlap detection
* Interval merging is a common interview pattern

---

### Problem Solved

* 56. Merge Intervals

<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/1cceb3fa-fa09-4ad4-91d0-d284d8e39355" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/a8180bc9-b225-419e-9d98-58459ab28ac2" />

