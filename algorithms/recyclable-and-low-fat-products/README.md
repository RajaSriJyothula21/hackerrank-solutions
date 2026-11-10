# Recyclable and Low Fat Products

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Recyclable and Low Fat Products](https://leetcode.com/problems/recyclable-and-low-fat-products/)

---

## Solutions

### 🗄️ MySQL (`solution.sql`)

- **Synchronized:** November 10, 2026
- **Language:** `MySQL`
- **Source File:** [`solution.sql`](solution.sql)

#### 💡 Approach & Intuition

> The query filters the products table using a `WHERE` clause to select only the rows where both the `low_fats` and `recyclable` columns are equal to 'Y', and projects the `product_id` column.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N)` — *The database engine must scan all N rows of the products table to evaluate the condition for each row.*
- **Space Complexity:** `O(1)` — *The result set is generated on the fly and returned without requiring any additional auxiliary data structures proportional to the input size.*
