# Two Sum

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Two Sum](https://leetcode.com/problems/two-sum/)

---

## Solutions

### ☕ Java (`solution.java`)

- **Synchronized:** October 14, 2026
- **Language:** `Java`
- **Source File:** [`solution.java`](solution.java)

#### 💡 Approach & Intuition

> This solution uses a brute-force approach by checking every possible pair of integers in the array to see if their sum equals the target.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N^2)` — *The nested loops iterate approximately N*(N-1)/2 times, resulting in quadratic time complexity relative to the array length N.*
- **Space Complexity:** `O(1)` — *The algorithm uses a constant amount of extra space regardless of the input array size.*
