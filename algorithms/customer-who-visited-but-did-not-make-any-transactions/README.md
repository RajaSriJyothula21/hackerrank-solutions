# Customer Who Visited but Did Not Make Any Transactions

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Customer Who Visited but Did Not Make Any Transactions](https://leetcode.com/problems/customer-who-visited-but-did-not-make-any-transactions/)

---

## Solutions

### 🗄️ MySQL (`solution.sql`)

- **Synchronized:** November 10, 2026
- **Language:** `MySQL`
- **Source File:** [`solution.sql`](solution.sql)

#### 💡 Approach & Intuition

> The query performs a LEFT JOIN between the Visits and Transactions tables, filters for visits that lack a corresponding transaction (where transaction_id is NULL), and groups the results by customer_id to count the unmatched visits.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N log N + M log M)` — *The time complexity is dominated by the join and grouping operations on the Visits table of size N and Transactions table of size M, which typically require sorting or hashing.*
- **Space Complexity:** `O(N + M)` — *The space complexity accounts for the internal memory required to store and process the rows from both tables during the join and group-by operations.*
