
# Priority Queue (Heap) – Day Notes

Today I learned the **Priority Queue (Heap)** data structure and solved multiple problems using **max heap and min heap patterns**.

---

## Core Idea

A priority queue always gives access to the **highest priority element** first.

* **Max Heap** → Largest element at the top
* **Min Heap** → Smallest element at the top

This helps solve problems where we repeatedly need the **maximum or minimum value**.

---

## Problems Solved

---

### 2974 – Minimum Number Game

**Logic:**

* Sort or use min heap to process numbers in pairs
* Pick the smallest two numbers at a time
* Rearrange according to given rules

**Learning:**
Priority-based ordering makes pair selection easier.

---

### 2558 – Take Gifts From the Richest Pile

**Logic:**

* Use max heap to always select the largest pile
* Reduce the largest value and push it back
* Repeat operation `k` times

**Learning:**
Max heap is useful when repeatedly modifying the largest element.

---

### 2182 – Construct String With Repeat Limit

**Logic:**

* Use max heap to always pick the largest available character
* Append characters up to repeat limit
* Use second largest character when limit is reached
* Push remaining frequencies back

**Learning:**
Priority queue helps build lexicographically largest string under constraints.

---

## Key Learning

* Priority Queue gives fast access to extreme values
* Useful for greedy problems
* Helps optimize repeated max/min operations
* Combining heap with hashmap is common

---

## Patterns Practiced

* Greedy with Max Heap
* Greedy with Min Heap
* Frequency-based heap usage

---

## Problems Practiced Today

* 2974 – Minimum Number Game
* 2558 – Take Gifts From the Richest Pile
* 2182 – Construct String With Repeat Limit

