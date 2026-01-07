
### Two Pointers (Left–Right) – Daily Notes

Today I practiced problems based on the **Two Pointers technique** using `left` and `right` pointers starting from the beginning and end of the array.

The idea is to **move pointers based on a condition** to reduce the search space and solve problems efficiently.

---

### Core Idea

* Sort the array (if needed)
* Place one pointer at the **start (left)**
* Place one pointer at the **end (right)**
* Check a condition using `nums[left]` and `nums[right]`
* Move pointers:

  * Move `left` forward when a larger value is needed
  * Move `right` backward when a smaller value is needed

---

### Number of Subsequences That Satisfy the Given Sum Condition

* Fix the smallest value using `left`
* Check with the largest value using `right`
* If `min + max` is valid, all combinations in between are valid
* Count subsequences and move `left`
* Otherwise, move `right`

---

### Sum of Square Numbers

* Use two pointers from `0` and `sqrt(c)`
* Check if `left² + right²` equals the given number
* Increase `left` if sum is small, decrease `right` if sum is large

---

### Boats to Save People

* Pair the lightest and heaviest person
* If they fit in one boat, move both pointers
* Otherwise, move only the `right` pointer
* Each iteration uses one boat

---

### Minimize Maximum Pair Sum in Array

* Pair smallest and largest elements
* Track the maximum pair sum
* Move both pointers inward after pairing

---

### Why Two Pointers Work

* Avoids checking all pairs
* Uses sorted order to make smart decisions
* Reduces time complexity from **O(n²)** to **O(n)** in many cases

---

### Problems Solved Today

* Number of Subsequences That Satisfy the Given Sum Condition
* Sum of Square Numbers
* Boats to Save People
* Minimize Maximum Pair Sum in Array
![WhatsApp Image 2026-01-07 at 1 52 13 PM](https://github.com/user-attachments/assets/56027ec6-1281-4754-8b28-a70324c6a472)
![WhatsApp Image 2026-01-07 at 1 52 25 PM](https://github.com/user-attachments/assets/f83d939f-406b-48d6-92b2-a5ec60997205)
![WhatsApp Image 2026-01-07 at 1 52 32 PM](https://github.com/user-attachments/assets/500a82fc-39fb-404e-ac2e-e78b2819ed19)
![WhatsApp Image 2026-01-07 at 1 52 53 PM](https://github.com/user-attachments/assets/83fba8ff-68a7-4759-940b-2261e0abf9b0)
![WhatsApp Image 2026-01-07 at 1 53 01 PM](https://github.com/user-attachments/assets/19f56d8b-7987-418f-909c-f45bd16026c1)
![WhatsApp Image 2026-01-07 at 1 53 08 PM](https://github.com/user-attachments/assets/e116f592-4946-4339-b5f9-78098afe35a0)
![WhatsApp Image 2026-01-07 at 1 53 33 PM](https://github.com/user-attachments/assets/ba9cdb47-1754-44f0-92ee-ba58204f4d8c)


