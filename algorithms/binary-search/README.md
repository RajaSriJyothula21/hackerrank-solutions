# Binary Search

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Binary Search](https://leetcode.com/problems/binary-search/)

---

## Solutions

### ☕ Java — Approach 4 (`solution_4.java`)

- **Synchronized:** October 26, 2026
- **Language:** `Java`
- **Source File:** [`solution_4.java`](solution_4.java)

#### 💡 Approach & Intuition

> The algorithm implements standard binary search by repeatedly dividing the search interval in half until the target value is found or the interval is empty.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(log N)` — *The search space is halved in each iteration of the while loop, resulting in a logarithmic number of steps relative to the array size N.*
- **Space Complexity:** `O(1)` — *The algorithm only uses a few primitive variables (low, high, mid) which require constant extra space regardless of the input size.*

---

### ☕ Java — Approach 2 (`solution_2.java`)

- **Synchronized:** October 26, 2026
- **Language:** `Java`
- **Source File:** [`solution_2.java`](solution_2.java)

#### 💡 Approach & Intuition

> The solution implements standard binary search by iteratively dividing the search space in half until the target is found or the pointers cross.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(log N)` — *The search space is halved in each iteration of the while loop, leading to a logarithmic number of steps relative to the array size N.*
- **Space Complexity:** `O(1)` — *Only a few primitive integer variables (low, high, mid) are used for pointers, requiring constant extra space regardless of the input size.*

---

### ☕ Java (`solution.java`)

- **Synchronized:** October 26, 2026
- **Language:** `Java`
- **Source File:** [`solution.java`](solution.java)

#### 💡 Approach & Intuition

> The algorithm uses binary search to repeatedly divide the search interval in half by comparing the target with the middle element until found or the pointers cross.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(log N)` — *The search space is halved in each iteration of the while loop, resulting in a logarithmic number of steps relative to the array size N.*
- **Space Complexity:** `O(1)` — *The algorithm only uses a constant number of scalar variables (low, high, mid) which require a fixed amount of extra memory regardless of input size.*
