
### Monotonic Stack – Daily Temperatures (Day Notes)

Today I solved **LeetCode 739 – Daily Temperatures** using the **monotonic decreasing stack pattern**.

---

### Core Idea

For each day, find how many days you have to wait to get a **warmer temperature**.
Use a stack to keep track of **indices of days with decreasing temperatures**.

---

### Problem Logic

The goal is to calculate the distance between the current day and the next day with a higher temperature.

---

### Approach

* Traverse the temperature array from left to right
* Maintain a stack that stores indices of temperatures in **decreasing order**
* When the current temperature is greater than the temperature at the stack top:

  * Pop the index from the stack
  * Calculate the difference between current index and popped index
* Push the current index into the stack

---

### Why Monotonic Stack Works

* Keeps unresolved colder days in the stack
* When a warmer day appears, it resolves multiple previous days efficiently
* Each element is pushed and popped only once

---

### Key Learning

* Stack should store **indices**, not values
* Distance calculation depends on index difference
* Monotonic stack is useful for “next greater” type problems

---

### Problem Solved

* 739. Daily Temperatures

![WhatsApp Image 2026-01-24 at 11 10 28 PM](https://github.com/user-attachments/assets/3ea209ef-2422-4b6c-ba9d-91c3fda16dab)
![WhatsApp Image 2026-01-24 at 11 10 38 PM](https://github.com/user-attachments/assets/33bd371a-bd2c-49a3-a047-d94ddb0b07bb)
![WhatsApp Image 2026-01-24 at 11 10 43 PM](https://github.com/user-attachments/assets/2c630044-d6d7-4b50-9a6d-714755a99531)
