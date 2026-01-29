

# Two Pointer Revision Notes

Today I revised multiple **two-pointer based problems** to strengthen pointer movement logic, boundary handling, and condition-based decisions.

---

## Sorted Array Two Pointer Problems

### Container With Most Water (11)

**Logic:**
Use left and right pointers.
Move the pointer with the smaller height to maximize area.

---

### Number of Subsequences That Satisfy Condition (1498)

**Logic:**
Sort array and use two pointers.
If `nums[left] + nums[right] <= target`, count all valid subsequences between them.

---

### Sum of Square Numbers (633)

**Logic:**
Use two pointers from `0` and `sqrt(c)`.
Adjust pointers based on sum of squares.

---

### Boats to Save People (881)

**Logic:**
Pair lightest and heaviest people.
If they exceed limit, move heavy pointer only.

---

### Minimize Maximum Pair Sum (1877)

**Logic:**
Pair smallest with largest.
Track maximum sum among all pairs.

---

## String & Character Two Pointer Problems

### Valid Palindrome (125)

**Logic:**
Use left and right pointers.
Skip non-alphanumeric characters and compare letters.

---

### Reverse String (344)

**Logic:**
Swap characters using left and right pointers.

---

### Reverse Vowels of a String (345)

**Logic:**
Move pointers and swap only vowels.

---

### Valid Palindrome II (680)

**Logic:**
On first mismatch, try skipping left or right once.

---

### Reverse Only Letters (917)

**Logic:**
Skip non-letter characters and swap only alphabet characters.

---

## Array In-place Two Pointer Problems

### Remove Element (27)

**Logic:**
Use read and write pointers.
Overwrite unwanted values in the same array.

---

## Key Learning From Revision

* Two pointers reduce nested loops
* Pointer movement depends on problem constraints
* Sorting enables efficient left–right traversal
* In-place modification avoids extra space
* Boundary and condition checks are very important

---

## Problems Revised Today

* 11 — Container With Most Water
* 1498 — Number of Subsequences That Satisfy Condition
* 633 — Sum of Square Numbers
* 881 — Boats to Save People
* 1877 — Minimize Maximum Pair Sum
* 125 — Valid Palindrome
* 344 — Reverse String
* 345 — Reverse Vowels of a String
* 680 — Valid Palindrome II
* 917 — Reverse Only Letters
* 27 — Remove Element


<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/896d0380-e554-4b58-984d-b841706bfc61" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/c4898f46-9a7f-4c76-9d9d-54c5826ad2c5" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/6b969db7-086d-4555-8ace-220e46d63db6" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/a2ef1e03-8c03-4900-9c3c-993b43b4c137" />
