# Count Number of Pairs With Absolute Difference K

**Difficulty:** Easy  |  **Acceptance:** 85.4%

**Tags:** `Array`, `Hash Table`, `Counting`

## Problem

Given an integer array nums and an integer k, return the number of pairs (i, j) where i < j such that |nums[i] - nums[j]| == k.

The value of |x| is defined as:

	x if x >= 0.
	-x if x < 0.

&nbsp;
Example 1:

Input: nums = [1,2,2,1], k = 1
Output: 4
Explanation: The pairs with an absolute difference of 1 are:
- [1,2,2,1]
- [1,2,2,1]
- [1,2,2,1]
- [1,2,2,1]

Example 2:

Input: nums = [1,3], k = 3
Output: 0
Explanation: There are no pairs with an absolute difference of 3.

Example 3:

Input: nums = [3,2,1,5,4], k = 2
Output: 3
Explanation: The pairs with an absolute difference of 2 are:
- [3,2,1,5,4]
- [3,2,1,5,4]
- [3,2,1,5,4]

&nbsp;
Constraints:

	1 <= nums.length <= 200
	1 <= nums[i] <= 100
	1 <= k <= 99

## My Submission

- Runtime: 115 ms
- Memory: 17.7 MB

## Similar Problems

- [Two Sum](https://leetcode.com/problems/two-sum/) — Easy
- [K-diff Pairs in an Array](https://leetcode.com/problems/k-diff-pairs-in-an-array/) — Medium
- [Finding Pairs With a Certain Sum](https://leetcode.com/problems/finding-pairs-with-a-certain-sum/) — Medium
- [Count Equal and Divisible Pairs in an Array](https://leetcode.com/problems/count-equal-and-divisible-pairs-in-an-array/) — Easy
- [Count Number of Bad Pairs](https://leetcode.com/problems/count-number-of-bad-pairs/) — Medium
