# Article Views I

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Article Views I](https://leetcode.com/problems/article-views-i/)

---

## Solutions

### 🗄️ MySQL (`solution.sql`)

- **Synchronized:** November 10, 2026
- **Language:** `MySQL`
- **Source File:** [`solution.sql`](solution.sql)

#### 💡 Approach & Intuition

> The query selects distinct author IDs from the views table where the author viewed their own article, and then sorts the resulting IDs in ascending order.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N log N)` — *Scanning the rows takes O(N) time and sorting the unique IDs takes O(K log K) time, where K is the number of unique authors.*
- **Space Complexity:** `O(K)` — *Auxiliary space is used to store the hash set or temporary sorting structures for the unique author IDs.*
