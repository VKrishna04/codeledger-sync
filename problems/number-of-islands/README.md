# [200] Number of Islands
**Difficulty:** Medium  |  **Acceptance:** 64.3%  |  **Likes:** 25040 / **Dislikes:** 619
**Tags:** `Array`, `Depth-First Search`, `Breadth-First Search`, `Union-Find`, `Matrix`
## Problem
Given an m x n 2D binary grid grid which represents a map of '1's (land) and '0's (water), return the number of islands.

An island is surrounded by water and is formed by connecting adjacent lands horizontally or vertically. You may assume all four edges of the grid are all surrounded by water.

&nbsp;
Example 1:

Input: grid = [
  ["1","1","1","1","0"],
  ["1","1","0","1","0"],
  ["1","1","0","0","0"],
  ["0","0","0","0","0"]
]
Output: 1

Example 2:

Input: grid = [
  ["1","1","0","0","0"],
  ["1","1","0","0","0"],
  ["0","0","1","0","0"],
  ["0","0","0","1","1"]
]
Output: 3

&nbsp;
Constraints:

	m == grid.length
	n == grid[i].length
	1 <= m, n <= 300
	grid[i][j] is '0' or '1'.
## My Submission

- Runtime: 228 ms (beats 93.7%)
- Memory: 21.6 MB (beats 72.3%)

## Similar Problems

- [Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) — Medium
- [Battleships in a Board](https://leetcode.com/problems/battleships-in-a-board/) — Medium
- [Max Area of Island](https://leetcode.com/problems/max-area-of-island/) — Medium
- [Count Sub Islands](https://leetcode.com/problems/count-sub-islands/) — Medium
- [Find All Groups of Farmland](https://leetcode.com/problems/find-all-groups-of-farmland/) — Medium
