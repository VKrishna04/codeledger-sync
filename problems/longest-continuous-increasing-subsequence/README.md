# Longest Continuous Increasing Subsequence

**Difficulty:** Easy  |  **Acceptance:** 52.0%

**Tags:** `Array`

## Problem

Given an unsorted array of integers nums, return the length of the longest continuous increasing subsequence (i.e. subarray). The subsequence must be strictly increasing.

A continuous increasing subsequence is defined by two indices l and r (l < r) such that it is [nums[l], nums[l + 1], ..., nums[r - 1], nums[r]] and for each l <= i < r, nums[i] < nums[i + 1].

&nbsp;
Example 1:

Input: nums = [1,3,5,4,7]
Output: 3
Explanation: The longest continuous increasing subsequence is [1,3,5] with length 3.
Even though [1,3,5,7] is an increasing subsequence, it is not continuous as elements 5 and 7 are separated by element
4.

Example 2:

Input: nums = [2,2,2,2,2]
Output: 1
Explanation: The longest continuous increasing subsequence is [2] with length 1. Note that it must be strictly
increasing.

&nbsp;
Constraints:

	1 <= nums.length <= 104
	-109 <= nums[i] <= 109

## My Submission

- Runtime: 4 ms
- Memory: 18.8 MB

## Similar Problems

- [Number of Longest Increasing Subsequence](https://leetcode.com/problems/number-of-longest-increasing-subsequence/) — Medium
- [Consecutive Characters](https://leetcode.com/problems/consecutive-characters/) — Easy
- [Longest Increasing Subsequence II](https://leetcode.com/problems/longest-increasing-subsequence-ii/) — Hard
