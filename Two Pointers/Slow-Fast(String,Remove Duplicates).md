
### Two Pointers – In-place Processing (Day Notes)

Today I practiced problems that use the **two-pointer technique** to modify arrays and strings **in-place** without using extra memory.

---

### String Compression (443)

**Logic:**
Traverse the character array and group consecutive identical characters.
Write the character and its frequency (if greater than one) back into the same array using a write pointer.

**Key idea:**
Use one pointer for reading and another pointer for writing compressed output.

---

### Remove Duplicates from Sorted Array

**Logic:**
Traverse the sorted array and keep only unique elements.
Overwrite duplicate values by storing only new elements at the front of the array.

**Key idea:**
Since duplicates are adjacent in a sorted array, they can be skipped easily.

---

### Key Learning

* Two pointers help perform in-place operations efficiently
* One pointer reads data, the other writes results
* Useful for filtering, compression, and removing duplicates

---

### Problems Solved

* 443. String Compression
* 26. Remove Duplicates from Sorted Array
      
![WhatsApp Image 2026-01-16 at 1 54 57 PM](https://github.com/user-attachments/assets/68e029f4-c185-4994-8014-adf13b6334e3)
![WhatsApp Image 2026-01-16 at 1 55 08 PM](https://github.com/user-attachments/assets/8ceff21d-6b34-47ec-bd46-d8f15f49c599)


