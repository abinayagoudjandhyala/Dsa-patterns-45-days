
### Interval Patterns – Insert & Remove Overlaps (Day Notes)

Today I solved two important **interval-based greedy problems** focusing on **insertion and overlap removal**.

---

## Insert Interval (57)

### Core Idea

Insert a new interval into a sorted list of non-overlapping intervals and merge overlapping intervals if needed.

---

### Logic

* Copy all intervals that end before the new interval starts
* Merge all overlapping intervals with the new interval
* Insert the merged interval
* Copy remaining intervals

---

### Overlap Condition

```
interval.start ≤ newInterval.end
```

Non-overlap condition:

```
interval.end < newInterval.start
```

---

### Key Learning

* Careful boundary comparison is important
* Merging while inserting avoids extra passes
* Two-pointer scanning makes insertion efficient

---

## Non-overlapping Intervals (435)

### Core Idea

Remove the minimum number of intervals so that the remaining intervals do not overlap.

---

### Logic

* Sort intervals by ending time
* Always keep the interval with the **earliest ending time**
* Count how many non-overlapping intervals can be selected
* Remove the remaining ones

---

### Non-overlap Condition

```
current.start ≥ previous.end
```

---

### Key Learning

* Greedy strategy works best for interval removal problems
* Choosing earliest finishing interval leaves more room for others
* Sorting by end time is critical

---

## Overall Learning

* Interval problems require careful comparison logic
* Greedy and two-pointer techniques are very effective
* Boundary handling is crucial for correctness

---

### Problems Solved

* 57. Insert Interval
* 435. Non-overlapping Intervals
       
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/c40cec2a-7794-43b2-8097-42468273fb7f" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/93dd84e2-a0dd-4712-86ab-7cfd14f2a13f" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/586731e1-d559-487a-b3fa-84711c2c2018" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/3948d543-187a-4bbf-8dba-b4d39bfd0643" />

