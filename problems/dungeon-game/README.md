# Dungeon Game

**Difficulty:** Hard  |  **Acceptance:** 41.3%

**Tags:** `Array`, `Dynamic Programming`, `Matrix`

## Problem

The demons had captured the princess and imprisoned her in the bottom-right corner of a dungeon. The dungeon consists of m x n rooms laid out in a 2D grid. Our valiant knight was initially positioned in the top-left room and must fight his way through dungeon to rescue the princess.

The knight has an initial health point represented by a positive integer. If at any point his health point drops to 0 or below, he dies immediately.

Some of the rooms are guarded by demons (represented by negative integers), so the knight loses health upon entering these rooms; other rooms are either empty (represented as 0) or contain magic orbs that increase the knight's health (represented by positive integers).

To reach the princess as quickly as possible, the knight decides to move only rightward or downward in each step.

Return the knight's minimum initial health so that he can rescue the princess.

Note that any room can contain threats or power-ups, even the first room the knight enters and the bottom-right room where the princess is imprisoned.

&nbsp;
Example 1:

Input: dungeon = [[-2,-3,3],[-5,-10,1],[10,30,-5]]
Output: 7
Explanation: The initial health of the knight must be at least 7 if he follows the optimal path: RIGHT-> RIGHT -> DOWN -> DOWN.

Example 2:

Input: dungeon = [[0]]
Output: 1

&nbsp;
Constraints:

	m == dungeon.length
	n == dungeon[i].length
	1 <= m, n <= 200
	-1000 <= dungeon[i][j] <= 1000

## My Submission

- Runtime: 3 ms
- Memory: 20.1 MB

## Similar Problems

- [Unique Paths](https://leetcode.com/problems/unique-paths/) — Medium
- [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) — Medium
- [Cherry Pickup](https://leetcode.com/problems/cherry-pickup/) — Hard
- [Minimum Path Cost in a Grid](https://leetcode.com/problems/minimum-path-cost-in-a-grid/) — Medium
- [Paths in Matrix Whose Sum Is Divisible by K](https://leetcode.com/problems/paths-in-matrix-whose-sum-is-divisible-by-k/) — Hard
