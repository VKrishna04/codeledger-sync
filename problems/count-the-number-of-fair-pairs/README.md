# Count the Number of Fair Pairs

**Difficulty:** Medium  |  **Acceptance:** 52.7%

**Tags:** `Array`, `Two Pointers`, `Binary Search`, `Sorting`

## Problem

Given a 0-indexed integer array nums of size n and two integers lower and upper, return the number of fair pairs.

A pair (i, j) is fair if:

	0 <= i < j < n, and
	lower <= nums[i] + nums[j] <= upper

&nbsp;
Example 1:

Input: nums = [0,1,7,4,4,5], lower = 3, upper = 6
Output: 6
Explanation: There are 6 fair pairs: (0,3), (0,4), (0,5), (1,3), (1,4), and (1,5).

Example 2:

Input: nums = [1,7,9,2,5], lower = 11, upper = 11
Output: 1
Explanation: There is a single fair pair: (2,3).

&nbsp;
Constraints:

	1 <= nums.length <= 105
	nums.length == n
	-109&nbsp;<= nums[i] <= 109
	-109&nbsp;<= lower <= upper <= 109

## My Submission

- Runtime: 267 ms
- Memory: 32.2 MB

## Similar Problems

- [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) — Hard
- [Finding Pairs With a Certain Sum](https://leetcode.com/problems/finding-pairs-with-a-certain-sum/) — Medium
- [Count Number of Pairs With Absolute Difference K](https://leetcode.com/problems/count-number-of-pairs-with-absolute-difference-k/) — Easy
- [Count Pairs Whose Sum is Less than Target](https://leetcode.com/problems/count-pairs-whose-sum-is-less-than-target/) — Easy
