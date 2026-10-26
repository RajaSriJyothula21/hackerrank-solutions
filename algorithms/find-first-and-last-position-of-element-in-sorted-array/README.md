# Find First and Last Position of Element in Sorted Array

**Difficulty:** 🟡 **Medium**  
**LeetCode Link:** [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)

---

## Solutions

### ☕ Java (`solution.java`)

- **Synchronized:** October 26, 2026
- **Language:** `Java`
- **Source File:** [`solution.java`](solution.java)

#### 💡 Approach & Intuition

> The solution uses two modified binary searches to independently find the first (lower) and last (higher) occurrences of the target value in the sorted array.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(log N)` — *Two separate binary searches are performed on the array of size N, each taking logarithmic time.*
- **Space Complexity:** `O(1)` — *Only a constant number of variables (pointers and indices) are used for the binary search operations, requiring no extra auxiliary data structures.*
