# Search Insert Position

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Search Insert Position](https://leetcode.com/problems/search-insert-position/)

---

## Solutions

### ☕ Java (`solution.java`)

- **Synchronized:** October 26, 2026
- **Language:** `Java`
- **Source File:** [`solution.java`](solution.java)

#### 💡 Approach & Intuition

> The algorithm uses binary search to find the lower bound of the target, maintaining a search range that halves with each iteration to find the insertion index efficiently.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(log N)` — *The search space is halved in each of the iterations of the while loop, where N is the length of the input array.*
- **Space Complexity:** `O(1)` — *Only a constant number of primitive variables (low, high, ans, mid) are used for tracking indices regardless of the input size.*
