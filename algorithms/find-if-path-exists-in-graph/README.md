# Find if Path Exists in Graph

**Difficulty:** 🟢 **Easy**  
**LeetCode Link:** [Find if Path Exists in Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/)

---

## Solutions

### ☕ Java (`solution.java`)

- **Synchronized:** October 14, 2026
- **Language:** `Java`
- **Source File:** [`solution.java`](solution.java)

#### 💡 Approach & Intuition

> The solution builds an adjacency list representation of the undirected graph from the given edges and uses Depth-First Search (DFS) to explore paths starting from the source until the destination is reached.

#### ⏱️ Complexity Analysis

- **Time Complexity:** `O(V + E)` — *Building the graph takes O(V + E) time, and the DFS traversal visits each vertex and edge at most once, where V is the number of vertices (n) and E is the number of edges.*
- **Space Complexity:** `O(V + E)` — *The adjacency list requires O(V + E) space, and the visited array along with the DFS recursion stack takes O(V) space in the worst case.*
