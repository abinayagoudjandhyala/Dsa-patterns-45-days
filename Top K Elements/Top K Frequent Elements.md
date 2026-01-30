
# Frequency Bucket Pattern – Top K Frequent Elements (347)

Today I solved **LeetCode 347 – Top K Frequent Elements** using the **Bucket Sort (Frequency Indexing)** technique.

---

## Core Idea

Instead of sorting elements or using a heap, group numbers based on their **frequency count**.
Use frequency as an index to directly access most frequent elements.

---

## Logic

* Count frequency of each element using a hashmap
* Create an array of lists where index represents frequency
* Place elements into buckets based on their frequency
* Traverse buckets from highest frequency to lowest
* Collect first `k` elements

---

## Why This Works

* Maximum frequency is limited by array length
* Direct frequency indexing avoids sorting
* Allows fast retrieval of top frequent elements

---

## Key Learning

* Bucket indexing is faster than heap for frequency problems
* Frequency = array index mapping is powerful
* Useful when values repeat many times

---

## Complexity

* Time: **O(n)**
* Space: **O(n)**

More efficient than heap-based solution.

---

## Pattern Used

* Frequency Map + Bucket Sort
* Counting Style Approach

---

## Problem Solved

* 347. Top K Frequent Elements

<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/4cdf7fff-452d-4154-b941-8e9165f8c2ea" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/466e19dc-1ade-4c2c-9595-9050255df0f5" />
