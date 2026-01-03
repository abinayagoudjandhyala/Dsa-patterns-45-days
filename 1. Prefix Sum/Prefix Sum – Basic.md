
## Prefix Sum – Basic

### Logic
Prefix sum is used to preprocess an array so that range sums can be calculated fast.

Create a prefix array:

prefix[0] = arr[0]
prefix[i] = prefix[i-1] + arr[i]


Range sum from index `i` to `j`:

sum(i, j) = prefix[j] - prefix[i-1]

If `i == 0`:

sum(0, j) = prefix[j]


### Questions Solved
- Range Sum Query – Immutable (LeetCode 303)
- Running Sum of 1D Array (LeetCode 1480)

![WhatsApp Image 2026-01-03 at 10 41 52 PM](https://github.com/user-attachments/assets/69a66e30-3bad-4ec8-a0c9-c0d749f186e2)
![WhatsApp Image 2026-01-03 at 10 42 10 PM](https://github.com/user-attachments/assets/ddbb723d-1c62-4e3b-853a-9caa5e0efc5b)

