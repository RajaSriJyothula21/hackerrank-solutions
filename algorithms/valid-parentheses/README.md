# Valid Parentheses

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)

---

## Solutions

### ☕ Java (`solution.java`)

- **Synchronized:** November 1, 2026
- **Language:** `Java`
- **Source File:** [`solution.java`](solution.java)

#### 💡 Approach & Intuition

> The algorithm uses a stack to keep track of opening brackets as they appear, ensuring that closing brackets match the most recent unmatched opening bracket in Last-In, First-Out (LIFO) order.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N)` — *The algorithm iterates through each of the N characters in the string once, performing constant-time O(1) stack operations for each character.*
- **Space Complexity:** `O(N)` — *In the worst-case scenario where the string contains only opening brackets, the stack will store up to N characters.*
