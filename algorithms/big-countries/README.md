# Big Countries

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Big Countries](https://leetcode.com/problems/big-countries/)

---

## Solutions

### 🗄️ MySQL (`solution.sql`)

- **Synchronized:** November 10, 2026
- **Language:** `MySQL`
- **Source File:** [`solution.sql`](solution.sql)

#### 💡 Approach & Intuition

> The query filters the 'world' table using a WHERE clause with a logical OR operator to retrieve the name, population, and area of countries that have an area of at least 3,000,000 or a population of at least 25,000,000.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N)` — *The database engine must scan all N rows in the 'world' table to evaluate the condition for each country.*
- **Space Complexity:** `O(1)` — *The query processes and streams the matching rows without utilizing any additional data structures that scale with the input size.*
