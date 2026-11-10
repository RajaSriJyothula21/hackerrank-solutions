# Product Sales Analysis I

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Product Sales Analysis I](https://leetcode.com/problems/product-sales-analysis-i/)

---

## Solutions

### 🗄️ MySQL (`solution.sql`)

- **Synchronized:** November 10, 2026
- **Language:** `MySQL`
- **Source File:** [`solution.sql`](solution.sql)

#### 💡 Approach & Intuition

> The query performs an inner join between the Sales table and the Product table using the shared product_id column to retrieve the corresponding product names along with the sales years and prices.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N * M)` — *The time complexity is proportional to the number of rows in the Sales table (N) and Product table (M) due to the join operation.*
- **Space Complexity:** `O(N)` — *The space complexity depends on the memory required to store the intermediate or result set of the joined tables.*
