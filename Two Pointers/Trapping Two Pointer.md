
### Trapping Rain Water – Two Pointers

Today I solved the **Trapping Rain Water** problem using the **two-pointer technique**.

---

### Core Idea

The water trapped at any position depends on the **minimum of the maximum height on the left and right** minus the current height.

Instead of precomputing left and right maximum arrays, we can solve this efficiently using **two pointers**.

---

### Two Pointer Approach

* Place one pointer at the **start (left)** and one at the **end (right)**
* Maintain:

  * `maxLeft` → maximum height seen so far from the left
  * `maxRight` → maximum height seen so far from the right
* Move pointers inward based on height comparison

---

### Pointer Movement Logic

* If `height[left] <= height[right]`:

  * The left side limits the water
  * Update `maxLeft`
  * Water trapped = `maxLeft − height[left]`
  * Move `left` pointer forward

* Else:

  * The right side limits the water
  * Update `maxRight`
  * Water trapped = `maxRight − height[right]`
  * Move `right` pointer backward

---

### Why This Works

The side with the **smaller height** determines how much water can be trapped at that position.
The opposite side is guaranteed to have a taller boundary.

---

### Key Learning

* Always process the pointer with the smaller height
* No extra arrays needed
* Efficient one-pass solution

---

### Problem Solved

* Trapping Rain Water

![WhatsApp Image 2026-01-07 at 9 10 28 PM](https://github.com/user-attachments/assets/7721bc02-777f-487f-84ea-6dcdb0aa8ccb)
![WhatsApp Image 2026-01-07 at 9 10 44 PM](https://github.com/user-attachments/assets/d0c4ac75-4f63-4f7a-94c3-ca018e00b07a)
![WhatsApp Image 2026-01-07 at 9 11 08 PM](https://github.com/user-attachments/assets/05dc0a9b-416c-4d62-bcc6-b8c88659d195)

