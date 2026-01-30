
# Priority Queue – Kth Largest Element (Max Heap Approach)

Today I solved **LeetCode 215 – Kth Largest Element in an Array** using the **Max Heap (Priority Queue)** method.

---

## Core Idea

A **max heap** always keeps the **largest element at the top**.
By removing the largest elements one by one, the k-th removed element becomes the answer.

---

## Logic

* Insert all array elements into a max heap
* Remove the largest element **k-1 times**
* The element at the top after removals is the **k-th largest element**

---

## Why This Works

The heap maintains descending order internally, so repeated removal always gives the next largest value.

---

## Key Learning

* Max heap gives direct access to the largest element
* Useful when repeated maximum extraction is required
* Simple and easy to implement

---

## Complexity

* Time: **O(n log n)**
* Space: **O(n)**

---

## Problem Solved

* 215. Kth Largest Element in an Array
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/0e856b72-b950-4777-a8d6-2540ab13c33a" />
