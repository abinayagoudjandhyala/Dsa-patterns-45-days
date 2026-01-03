
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

