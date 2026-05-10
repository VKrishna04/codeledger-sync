# [45] Jump Game II
**Difficulty:** Medium  |  **Acceptance:** 42.8%  |  **Likes:** 16536 / **Dislikes:** 707
**Tags:** `Array`, `Dynamic Programming`, `Greedy`
## Problem
You are given a 0-indexed array of integers nums of length n. You are initially positioned at&nbsp;index 0.

Each element nums[i] represents the maximum length of a forward jump from index i. In other words, if you are at index i, you can jump to any index (i + j)&nbsp;where:

	0 <= j <= nums[i] and
	i + j < n

Return the minimum number of jumps to reach index n - 1. The test cases are generated such that you can reach index&nbsp;n - 1.

&nbsp;
Example 1:

Input: nums = [2,3,1,1,4]
Output: 2
Explanation: The minimum number of jumps to reach the last index is 2. Jump 1 step from index 0 to 1, then 3 steps to the last index.

Example 2:

Input: nums = [2,3,0,1,4]
Output: 2

&nbsp;
Constraints:

	1 <= nums.length <= 104
	0 <= nums[i] <= 1000
	It's guaranteed that you can reach nums[n - 1].
## My Submission

- Runtime: 2 ms (beats 91.9%)
- Memory: 20 MB (beats 66.7%)

## Similar Problems

- [Jump Game](https://leetcode.com/problems/jump-game/) — Medium
- [Jump Game III](https://leetcode.com/problems/jump-game-iii/) — Medium
- [Jump Game VII](https://leetcode.com/problems/jump-game-vii/) — Medium
- [Minimum Number of Visited Cells in a Grid](https://leetcode.com/problems/minimum-number-of-visited-cells-in-a-grid/) — Hard
- [Maximum Number of Jumps to Reach the Last Index](https://leetcode.com/problems/maximum-number-of-jumps-to-reach-the-last-index/) — Medium
