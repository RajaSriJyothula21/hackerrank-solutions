# Reverse Integer

**Difficulty:** 🟡 **Medium**  
**LeetCode Link:** [Reverse Integer](https://leetcode.com/problems/reverse-integer/)

---

## Solutions

### ☕ Java (`solution.java`)

- **Synchronized:** October 26, 2026
- **Language:** `Java`
- **Source File:** [`solution.java`](solution.java)

#### 💡 Approach & Intuition

> The algorithm extracts the digits of the integer one by one from right to left using modulo and division operators, building the reversed integer while checking for potential 32-bit integer overflow.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(log10(N))` — *The while loop runs a number of times proportional to the number of digits in x, which is base-10 logarithmic with respect to the input magnitude.*
- **Space Complexity:** `O(1)` — *Only a constant amount of extra space is used for integer variables regardless of the input size.*
