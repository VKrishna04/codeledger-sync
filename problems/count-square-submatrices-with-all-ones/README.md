# Count Square Submatrices with All Ones

**Difficulty:** Medium  |  **Acceptance:** 80.7%

**Tags:** `Array`, `Dynamic Programming`, `Matrix`

## Problem

Given a m * n matrix of ones and zeros, return how many square submatrices have all ones.

&nbsp;
Example 1:

Input: matrix =
[
&nbsp; [0,1,1,1],
&nbsp; [1,1,1,1],
&nbsp; [0,1,1,1]
]
Output: 15
Explanation: 
There are 10 squares of side 1.
There are 4 squares of side 2.
There is  1 square of side 3.
Total number of squares = 10 + 4 + 1 = 15.

Example 2:

Input: matrix = 
[
  [1,0,1],
  [1,1,0],
  [1,1,0]
]
Output: 7
Explanation: 
There are 6 squares of side 1.  
There is 1 square of side 2. 
Total number of squares = 6 + 1 = 7.

&nbsp;
Constraints:

	1 <= arr.length&nbsp;<= 300
	1 <= arr[0].length&nbsp;<= 300
	0 <= arr[i][j] <= 1

## My Submission

- Runtime: 40 ms
- Memory: 22.2 MB

## Similar Problems

- [Minimum Cost Homecoming of a Robot in a Grid](https://leetcode.com/problems/minimum-cost-homecoming-of-a-robot-in-a-grid/) — Medium
- [Count Fertile Pyramids in a Land](https://leetcode.com/problems/count-fertile-pyramids-in-a-land/) — Hard
