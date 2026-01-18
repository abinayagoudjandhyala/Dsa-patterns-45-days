
### String Matching – Two Pointers (Day Notes)

Today I solved **LeetCode 28 – Find the Index of the First Occurrence in a String** using a **two-pointer / substring matching approach**.

---

### Core Idea

Check whether the **pattern string (needle)** appears inside the **main string (haystack)** by comparing characters sequentially.

---

### Problem Logic

The task is to find the **starting index** of the first occurrence of the pattern string in the main string.
If the pattern is not found, return `-1`.

---

### Approach

* Iterate through the main string
* For each position, try to match characters of the pattern
* Compare characters one by one
* If all characters match, return the current index
* If a mismatch occurs, move to the next starting position

---

### Why This Works

* Direct character comparison ensures correctness
* Stops early when mismatch happens
* Simple and effective for basic string matching

---

### Key Learning

* Two pointers can be used for pattern matching
* Matching resets when a mismatch occurs
* Useful foundation for advanced string algorithms

---

### Problem Solved

* 28. Find the Index of the First Occurrence in a String
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/2820853c-3863-4ec2-92d9-8fa059d54468" />

