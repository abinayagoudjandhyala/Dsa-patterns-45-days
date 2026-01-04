
# Prefix Patterns – Daily Notes

## 1. Subarray Sum Equals K

### Logic
- Maintain a running prefix sum
- If `(currentPrefix - k)` was seen before,
  then a subarray with sum `k` exists
- Store `prefixSum → count` in hashmap

### Why It Works
The difference of two prefix sums gives the subarray sum.

### Base Case
```

map.put(0, 1)

```

---

## 2. Subarrays Divisible by K

### Logic
- Maintain running prefix sum
- Compute `remainder = prefixSum % k`
- If the same remainder appears again,
  the subarray between them is divisible by `k`
- Store `remainder → count` in hashmap

### Why It Works
Two prefix sums with the same remainder differ by a multiple of `k`.

### Base Case
```

map.put(0, 1)

```

---

## 3. Contiguous Array

### Logic
- Convert all `0` values to `-1`
- Now the problem becomes finding the **longest subarray with sum = 0**
- Use prefix sum while traversing the array

### Important Step
- Store the **first index** where a prefix sum appears
- When the same prefix sum appears again,
  subtract the **previous stored index** from the current index
  to get the subarray length

```

length = currentIndex - previousIndex

```

- Update the maximum length

### Why It Works
Same prefix sum means the subarray between the two indices has sum `0`,
which represents equal number of `0`s and `1`s.

### Base Case
```

map.put(0, -1)

```

---

## 4. Product of Array Except Self

### Logic
- Build prefix products from the left
- Build suffix products from the right
- Result at index `i`:
```

leftProduct[i] * rightProduct[i]

```

### Why It Works
Each index gets the product of all elements except itself
without using division.

---

## Problems Revised
- Subarray Sum Equals K
- Subarrays Divisible by K
- Contiguous Array
- Product of Array Except Self
```

![WhatsApp Image 2026-01-04 at 12 11 26 PM](https://github.com/user-attachments/assets/cf27413f-3765-4133-9e8b-128538f3f41c)
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/eb8f5f7f-3b45-4ee7-8898-359679f43289" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/ef84d71b-9ece-450a-b0ce-c332c2f00cb7" />



