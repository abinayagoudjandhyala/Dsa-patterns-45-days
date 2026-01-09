
### Two Pointers – Practice Notes (Day 8)

Today I practiced multiple problems using the **two-pointer technique**, mainly focusing on **reversing, swapping, skipping characters, and filtering elements**.

---

### Reverse Vowels of a String

Used two pointers from both ends.
Moved pointers until both pointed to vowels, then swapped them.
Only vowels were reversed, other characters stayed in the same position.

---

### Valid Palindrome II

Compared characters from both ends using two pointers.
When a mismatch occurred, skipped either the left or right character once and checked if the remaining string formed a palindrome.
This works because only one deletion is allowed.

---

### Reverse Only Letters

Used two pointers from the start and end.
Skipped non-letter characters and swapped only letters.
Non-letter characters remained unchanged.

---

### Remove Element

Traversed the array and kept a pointer for valid elements.
Overwrote elements that were not equal to the given value.
Returned the count of remaining elements after removal.

---


### Key Learning

Two pointers help solve array and string problems efficiently by reducing unnecessary comparisons.
Pointer movement depends on conditions like value comparison or character type.

---

### Problems Solved

Reverse Vowels of a String
Valid Palindrome II
Reverse Only Letters
Remove Element

![WhatsApp Image 2026-01-09 at 7 52 42 PM](https://github.com/user-attachments/assets/556abc00-2782-40fa-bd40-1276c5c17aa5)
![WhatsApp Image 2026-01-09 at 7 52 51 PM](https://github.com/user-attachments/assets/c88a8504-d59c-4bca-b7c4-4963610307d8)
![WhatsApp Image 2026-01-09 at 7 52 57 PM](https://github.com/user-attachments/assets/f095321a-326b-46f4-88b2-96b8ebd72489)
![WhatsApp Image 2026-01-09 at 7 53 03 PM](https://github.com/user-attachments/assets/b54039dc-c354-4ef7-8cc3-528e0d366305)
![WhatsApp Image 2026-01-09 at 7 53 11 PM](https://github.com/user-attachments/assets/e67d10d3-82a7-4f05-8b65-3f3a59e112d1)
![WhatsApp Image 2026-01-09 at 7 53 17 PM](https://github.com/user-attachments/assets/d1a82a15-87c9-45f7-bc2d-bb46d5bee464)


