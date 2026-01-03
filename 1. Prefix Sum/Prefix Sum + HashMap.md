
## Prefix Sum + HashMap (Today’s Learning)

Today I learned how to use **prefix sum with hashmap** to solve subarray problems efficiently.



### What is the idea?

We calculate a **running sum** while moving through the array.  
At each index, we check whether a **required value of prefix sum** was seen before.

If yes, then the subarray between those indices satisfies the condition.

---

### 1. Subarray Sum Equals K

**Logic:**
- Keep adding elements to form `prefixSum`
- If `(prefixSum - k)` was seen before,  
  it means the subarray in between has sum `k`
- Store prefix sums and their **counts** in hashmap

**Why hashmap?**  
Because the same prefix sum can occur multiple times, and each occurrence forms a valid subarray.

**Base case:**
```

map.put(0, 1)

```
This allows subarrays starting from index `0`.

---

### 2. Contiguous Array

**Logic:**
- Convert all `0`s to `-1`
- Now the problem becomes finding the **longest subarray with sum = 0**
- If the same prefix sum appears again,  
  the subarray between them has sum `0`
- Store prefix sum with its **first index** only

**Why it works?**  
Equal number of `0`s and `1`s gives total sum `0` after conversion.

**Base case:**
```

map.put(0, -1)

```

---

### 3. Subarrays Divisible by K

**Logic:**
- Calculate `prefixSum % k`
- If the same remainder appears again,  
  the subarray between them is divisible by `k`
- Store `remainder → count` in hashmap

**Why remainder?**  
If two prefix sums have the same remainder, their difference is divisible by `k`.

**Base case:**
```

map.put(0, 1)

```

---

### Problems Solved
- Subarray Sum Equals K
- Contiguous Array
- Subarrays Divisible by K
![WhatsApp Image 2026-01-04 at 12 41 38 AM](https://github.com/user-attachments/assets/c5f85a1e-1762-41fb-b877-8d7decba5c1b)
![WhatsApp Image 2026-01-04 at 12 41 48 AM](https://github.com/user-attachments/assets/1798791d-32b9-4461-9bc8-6a8bc6b74a13)
![WhatsApp Image 2026-01-04 at 12 41 56 AM](https://github.com/user-attachments/assets/c6b3336a-ba9e-4647-ba7f-b95b4d157790)
![WhatsApp Image 2026-01-04 at 12 42 27 AM](https://github.com/user-attachments/assets/1249208b-a7d6-496c-87ce-98df4e78ff3f)


