# Counting Bits

**Difficulty:** Easy  |  **Acceptance:** 80.6%

**Tags:** `Dynamic Programming`, `Bit Manipulation`

## Problem

Given an integer n, return an array ans of length n + 1 such that for each i (0 <= i <= n), ans[i] is the number of 1's in the binary representation of i.

&nbsp;
Example 1:

Input: n = 2
Output: [0,1,1]
Explanation:
0 --> 0
1 --> 1
2 --> 10

Example 2:

Input: n = 5
Output: [0,1,1,2,1,2]
Explanation:
0 --> 0
1 --> 1
2 --> 10
3 --> 11
4 --> 100
5 --> 101

&nbsp;
Constraints:

	0 <= n <= 105

&nbsp;
Follow up:

	It is very easy to come up with a solution with a runtime of O(n log n). Can you do it in linear time O(n) and possibly in a single pass?
	Can you do it without using any built-in function (i.e., like __builtin_popcount in C++)?

## My Submission

- Runtime: 11 ms
- Memory: 18.5 MB

## Similar Problems

- [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) — Easy
- [Sum of Values at Indices With K Set Bits](https://leetcode.com/problems/sum-of-values-at-indices-with-k-set-bits/) — Easy
- [Find the K-or of an Array](https://leetcode.com/problems/find-the-k-or-of-an-array/) — Easy
