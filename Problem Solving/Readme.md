# Advanced C Programming Problem Solving

This repository contains a collection of advanced C programming problems to test problem-solving skills and in-depth understanding of algorithms and data structures. The problems cover a wide range of topics including dynamic programming, backtracking, graph theory, and more.

## 1. **N-Queens Problem (Backtracking)**

**Problem:**
The N-Queens problem is a classic example of backtracking. Write a C program to solve the N-Queens problem, where you must place `N` queens on an `N x N` chessboard such that no two queens threaten each other.

**Task:**
- Print all the possible solutions to the N-Queens problem.
- Use backtracking to explore possible configurations efficiently.

---

## 2. **Longest Increasing Subsequence (LIS)**

**Problem:**
Given an unsorted array of integers, write a C program to find the length of the longest increasing subsequence (LIS) in the array.

**Example:**
- Input: `{10, 22, 9, 33, 21, 50, 41, 60, 80}`
- Output: `6` (The LIS is `{10, 22, 33, 50, 60, 80}`)

**Task:**
- Solve the problem using **dynamic programming**.
- Discuss the time and space complexity of your solution.

---

## 3. **0/1 Knapsack Problem**

**Problem:**
The 0/1 Knapsack problem is a famous dynamic programming problem. Given a set of items, each with a weight and value, determine the maximum value that can be obtained by selecting a subset of the items such that the total weight is less than or equal to a given capacity.

**Example:**
- Input:
  - Weights: `{2, 3, 4, 5}`
  - Values: `{3, 4, 5, 6}`
  - Capacity: `5`
- Output: `7` (Select items 1 and 2 with total weight `5` and total value `7`)

**Task:**
- Implement this problem using dynamic programming.
- Discuss both the time complexity and space complexity.

---

## 4. **Dijkstra’s Algorithm (Shortest Path)**

**Problem:**
Implement Dijkstra's algorithm to find the shortest path in a weighted graph from a given source vertex.

**Input:**
- A graph represented as an adjacency matrix.
- A source vertex.
  
**Example:**
- Input:
  - Graph: `{{0, 1, 4, INF, INF, INF}, {1, 0, 4, 2, 7, INF}, {4, 4, 0, 3, 5, INF}, {INF, 2, 3, 0, 4, 6}, {INF, 7, 5, 4, 0, 7}, {INF, INF, INF, 6, 7, 0}}`
  - Source: `0`
- Output: Shortest distances from vertex `0` to all other vertices.

**Task:**
- Implement Dijkstra’s algorithm efficiently using a priority queue (min-heap).
- Discuss the time complexity of the algorithm.

---

## 5. **Merge Intervals**

**Problem:**
Given a collection of intervals, merge all overlapping intervals and return an array of the non-overlapping intervals that cover all the intervals in the input.

**Example:**
- Input: `{{1, 3}, {2, 4}, {5, 7}, {6, 8}}`
- Output: `{{1, 4}, {5, 8}}`

**Task:**
- Sort the intervals based on the start times and then merge overlapping intervals.
- Implement a solution with O(n log n) time complexity.

---

## 6. **Find Strongly Connected Components (Kosaraju’s Algorithm)**

**Problem:**
Given a directed graph, find all the strongly connected components (SCCs) using **Kosaraju's algorithm**.

**Task:**
- Implement Kosaraju’s algorithm to find all the SCCs of a graph.
- Discuss the time complexity of your solution (O(V + E)).

---

## 7. **Travelling Salesman Problem (TSP)**

**Problem:**
The Travelling Salesman Problem (TSP) asks for the shortest possible route that visits each city exactly once and returns to the origin city. Write a C program to solve TSP using **dynamic programming** (Held-Karp algorithm).

**Example:**
- Input: A matrix representing the distances between cities.
- Output: The minimum distance to complete the tour.

**Task:**
- Solve the problem using dynamic programming with bitmasking.
- Analyze the time complexity of your approach (O(n^2 * 2^n)).

---

## 8. **Longest Palindromic Substring**

**Problem:**
Given a string, write a C program to find the longest palindromic substring in it.

**Example:**
- Input: `"babad"`
- Output: `"bab"` or `"aba"`

**Task:**
- Solve this problem using dynamic programming or expand-around-center approach.
- Discuss the time complexity of both approaches.

---

## 9. **Find the Median of Two Sorted Arrays**

**Problem:**
Given two sorted arrays, find the median of the two sorted arrays. The overall time complexity should be O(log(min(n, m))).

**Example:**
- Input: 
  - Array 1: `{1, 3}`
  - Array 2: `{2}`
- Output: `2.0`

**Task:**
- Implement an efficient solution using binary search.
- Discuss the time complexity of your approach.

---

## 10. **Max Flow Problem (Ford-Fulkerson Algorithm)**

**Problem:**
Implement the **Ford-Fulkerson algorithm** to find the maximum flow in a flow network.

**Input:**
- A graph represented by an adjacency matrix where the value at position `(i, j)` represents the capacity of the edge from vertex `i` to vertex `j`.
  
**Task:**
- Find the maximum flow from a source vertex to a sink vertex in the graph using Ford-Fulkerson’s algorithm.
- Discuss the time complexity of the solution.

---

## 11. **K-th Smallest Element in an Unsorted Array (Quickselect Algorithm)**

**Problem:**
Given an unsorted array, find the `k`-th smallest element in the array in linear time.

**Example:**
- Input: `{7, 10, 4, 3, 20, 15}`, k = `4`
- Output: `10`

**Task:**
- Use **Quickselect** (a variation of QuickSort) to find the `k`-th smallest element.
- Discuss the average and worst-case time complexity of your solution.

---

## 12. **Palindrome Partitioning**

**Problem:**
Given a string, partition it such that every substring is a palindrome. Return the minimum number of cuts needed for a palindrome partitioning of the string.

**Example:**
- Input: `"aab"`
- Output: `1` (The palindrome partitioning is `["aa", "b"]`)

**Task:**
- Solve the problem using dynamic programming.
- Discuss both time and space complexity.

---

## 13. **Counting Inversions in an Array**

**Problem:**
Write a C program to count the number of inversions in an array. An inversion is a pair of indices `(i, j)` such that `i < j` and `arr[i] > arr[j]`.

**Example:**
- Input: `{2, 4, 1, 3, 5}`
- Output: `3` (Inversions: `(2, 1)`, `(4, 1)`, `(4, 3)`)

**Task:**
- Implement this using a modified merge sort algorithm.
- Analyze the time complexity of the solution (O(n log n)).

---

## 14. **Word Break Problem**

**Problem:**
Given a string `s` and a dictionary of words, determine if `s` can be segmented into a space-separated sequence of dictionary words.

**Example:**
- Input: `"applepenapple"`, dictionary = `["apple", "pen"]`
- Output: `True` (can be segmented as `"apple pen apple"`)

**Task:**
- Solve this problem using dynamic programming.
- Discuss the time and space complexity of your solution.

---

## 15. **Largest Rectangle in Histogram**

**Problem:**
Given an array of integers representing the heights of bars in a histogram, write a C program to find the area of the largest rectangle that can be formed within the histogram.

**Example:**
- Input: `{2, 1, 5, 6, 2, 3}`
- Output: `10` (The largest rectangle is `5 * 2`)

**Task:**
- Solve the problem using a **monotonic stack** approach.
- Analyze the time and space complexity of the solution.

---

## Conclusion

These problems cover a broad range of advanced topics in C programming. Each problem is designed to improve your understanding of core concepts like dynamic programming, graph theory, backtracking, and more. By solving these problems, you will enhance your problem-solving skills and prepare for competitive programming challenges.
