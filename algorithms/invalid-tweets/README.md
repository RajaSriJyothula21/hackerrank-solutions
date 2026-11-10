# Invalid Tweets

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Invalid Tweets](https://leetcode.com/problems/invalid-tweets/)

---

## Solutions

### 🗄️ MySQL (`solution.sql`)

- **Synchronized:** November 10, 2026
- **Language:** `MySQL`
- **Source File:** [`solution.sql`](solution.sql)

#### 💡 Approach & Intuition

> The query selects the tweet IDs from the 'Tweets' table where the string length of the 'content' column is strictly greater than 15.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N)` — *A full table scan is performed to evaluate the length function for each of the N rows in the Tweets table.*
- **Space Complexity:** `O(1)` — *The operation is performed in-stream per row without requiring any additional proportional data structures in memory.*
