
# Revision Day Notes – Prefix Sum & Two Pointers

Today I revised **Prefix Sum patterns** and started revising **Two Pointer techniques** by solving multiple problems to strengthen logic and improve speed.

---

## Prefix Sum Pattern (Revised)

### Core Idea

Use cumulative sums to quickly calculate subarray and range sums without recalculating repeatedly.

---

### Problems Revised

#### Range Sum Query – Immutable (303)

Used prefix sum array to answer multiple range sum queries efficiently.

---

#### Running Sum of 1D Array (1480)

Built cumulative sum while traversing the array.

---

#### Subarray Sum Equals K (560)

Checked if `(currentSum - k)` exists using hashmap to count valid subarrays.

---

#### Contiguous Array (525)

Converted `0` to `-1` and found longest subarray with sum zero using prefix sum and hashmap.

---

#### Subarrays Divisible by K (974)

Used prefix sum remainder logic to count subarrays with same remainder.

---

#### Product of Array Except Self (238)

Used prefix product logic from left and right to compute result without division.

---

### Key Learning (Prefix)

* Prefix sum avoids repeated calculations
* HashMap helps track frequency of sums
* Useful for subarray counting and range queries

---

## Two Pointer Pattern (Revision Started)

### Core Idea

Use left and right pointers to efficiently process sorted arrays and reduce time complexity.

---

### Problems Revised

#### Two Sum II (167)

Used left and right pointers on sorted array to find target sum.

---

#### 3Sum (15)

Fixed one element and applied two-pointer technique to find remaining pair.

---

### Key Learning (Two Pointers)

* Pointer movement depends on condition comparison
* Sorting enables efficient two-pointer usage
* Helps reduce nested loops

---

## Overall Revision Outcome

* Strengthened prefix sum + hashmap logic
* Improved two-pointer implementation confidence
* Increased speed and accuracy while solving known patterns
* Built better problem recognition ability

---

## Problems Solved Today (Revision)

* 303 – Range Sum Query Immutable
* 1480 – Running Sum of 1D Array
* 560 – Subarray Sum Equals K
* 525 – Contiguous Array
* 974 – Subarrays Divisible by K
* 238 – Product of Array Except Self
* 167 – Two Sum II
* 15 – 3Sum

![WhatsApp Image 2026-01-25 at 8 59 11 PM](https://github.com/user-attachments/assets/8495b326-3527-4b8d-ac84-fac693cad135)
![WhatsApp Image 2026-01-25 at 8 59 25 PM](https://github.com/user-attachments/assets/4155ea7b-1fe6-4845-ae8e-299a2a224617)
![WhatsApp Image 2026-01-25 at 8 59 28 PM](https://github.com/user-attachments/assets/e2d818c6-c84e-41ff-9335-aa1ae835dad9)
![WhatsApp Image 2026-01-25 at 8 59 31 PM](https://github.com/user-attachments/assets/71490dbc-3521-4457-9b3f-fdb3fd0409ba)
