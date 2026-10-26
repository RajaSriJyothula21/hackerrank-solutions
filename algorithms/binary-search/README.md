# Binary Search

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Binary Search](https://leetcode.com/problems/binary-search/)

---

## Solutions

### ☕ Java (`solution.java`)

- **Synchronized:** October 26, 2026
- **Language:** `Java`
- **Source File:** [`solution.java`](solution.java)

#### 💡 Approach & Intuition

> The algorithm uses binary search to repeatedly divide the search interval in half by comparing the target with the middle element until found or the pointers cross.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(log N)` — *The search space is halved in each iteration of the while loop, resulting in a logarithmic number of steps relative to the array size N.*
- **Space Complexity:** `O(1)` — *The algorithm only uses a constant number of scalar variables (low, high, mid) which require a fixed amount of extra memory regardless of input size.*
