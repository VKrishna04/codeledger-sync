# Total Hamming Distance

**Difficulty:** Medium  |  **Acceptance:** 54.8%

**Tags:** `Array`, `Math`, `Bit Manipulation`

## Problem

The Hamming distance between two integers is the number of positions at which the corresponding bits are different.

Given an integer array nums, return the sum of Hamming distances between all the pairs of the integers in nums.

&nbsp;
Example 1:

Input: nums = [4,14,2]
Output: 6
Explanation: In binary representation, the 4 is 0100, 14 is 1110, and 2 is 0010 (just
showing the four bits relevant in this case).
The answer will be:
HammingDistance(4, 14) + HammingDistance(4, 2) + HammingDistance(14, 2) = 2 + 2 + 2 = 6.

Example 2:

Input: nums = [4,14,4]
Output: 4

&nbsp;
Constraints:

	1 <= nums.length <= 104
	0 <= nums[i] <= 109
	The answer for the given input will fit in a 32-bit integer.

## My Submission

- Runtime: 114 ms
- Memory: 20.1 MB

## Similar Problems

- [Hamming Distance](https://leetcode.com/problems/hamming-distance/) — Easy
- [Sum of Digit Differences of All Pairs](https://leetcode.com/problems/sum-of-digit-differences-of-all-pairs/) — Medium
