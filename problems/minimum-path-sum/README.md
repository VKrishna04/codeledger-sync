# Minimum Path Sum

**Difficulty:** Medium  |  **Acceptance:** 68.2%

**Tags:** `Array`, `Dynamic Programming`, `Matrix`

## Problem

Given a m x n grid filled with non-negative numbers, find a path from top left to bottom right, which minimizes the sum of all numbers along its path.

Note: You can only move either down or right at any point in time.

&nbsp;
Example 1:

Input: grid = [[1,3,1],[1,5,1],[4,2,1]]
Output: 7
Explanation: Because the path 1 &rarr; 3 &rarr; 1 &rarr; 1 &rarr; 1 minimizes the sum.

Example 2:

Input: grid = [[1,2,3],[4,5,6]]
Output: 12

&nbsp;
Constraints:

	m == grid.length
	n == grid[i].length
	1 <= m, n <= 200
	0 <= grid[i][j] <= 200

## My Submission

- Runtime: 11 ms
- Memory: 21.8 MB

## Similar Problems

- [Unique Paths](https://leetcode.com/problems/unique-paths/) — Medium
- [Dungeon Game](https://leetcode.com/problems/dungeon-game/) — Hard
- [Cherry Pickup](https://leetcode.com/problems/cherry-pickup/) — Hard
- [Minimum Path Cost in a Grid](https://leetcode.com/problems/minimum-path-cost-in-a-grid/) — Medium
- [Maximum Number of Points with Cost](https://leetcode.com/problems/maximum-number-of-points-with-cost/) — Medium
