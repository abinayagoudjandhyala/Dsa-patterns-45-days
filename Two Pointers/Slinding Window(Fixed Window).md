

### Sliding Window – Fixed Window Size (Day Notes)

Today I solved **LeetCode 643 – Maximum Average Subarray I** using the **fixed-size sliding window technique**.

---

### Core Idea

Maintain the sum of a window of size `k` and slide the window across the array.
Update the sum by removing the left element and adding the new right element.

---

### Problem Logic

The task is to find the **maximum average** among all contiguous subarrays of length `k`.

---

### Approach

* Compute the sum of the first `k` elements
* Use this as the initial window sum
* Slide the window one step at a time
* Update the sum efficiently
* Track the maximum sum

---

### Why Sliding Window Works

* Avoids recalculating sums for each window
* Processes the array in one pass
* Reduces time complexity to linear time

---

### Key Learning

* Fixed-size sliding windows are useful for subarray problems
* Efficient sum updates make the solution faster
* Simple pattern with strong practical usage

---

### Problem Solved

* 643. Maximum Average Subarray I

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/c230e90c-49b5-43db-ae85-d671973226f2" />


 
