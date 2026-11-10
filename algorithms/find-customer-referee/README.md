# Find Customer Referee

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Find Customer Referee](https://leetcode.com/problems/find-customer-referee/)

---

## Solutions

### 🗄️ MySQL (`solution.sql`)

- **Synchronized:** November 10, 2026
- **Language:** `MySQL`
- **Source File:** [`solution.sql`](solution.sql)

#### 💡 Approach & Intuition

> The solution filters the customer table using a WHERE clause to select names where the referee ID is either not equal to 2 or is explicitly NULL.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N)` — *The database engine scans the entire table of N rows to evaluate the condition for each record.*
- **Space Complexity:** `O(1)` — *The query executes in-place without requiring any additional data structures proportional to the input size.*
