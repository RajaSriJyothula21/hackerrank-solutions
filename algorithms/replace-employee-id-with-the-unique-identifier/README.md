# Replace Employee ID With The Unique Identifier

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Replace Employee ID With The Unique Identifier](https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/)

---

## Solutions

### 🗄️ MySQL (`solution.sql`)

- **Synchronized:** November 10, 2026
- **Language:** `MySQL`
- **Source File:** [`solution.sql`](solution.sql)

#### 💡 Approach & Intuition

> The query performs a left join between the Employees table and the EmployeeUNI table on the employee ID to retrieve the unique identifier and name for every employee.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(N + M)` — *The database must scan and join the Employees table (size N) and the EmployeeUNI table (size M) based on the ID column.*
- **Space Complexity:** `O(N)` — *The database engine requires temporary memory proportional to the size of the result set or intermediate join tables to process the query.*
