# Container With Most Water

**Difficulty:** Medium  |  **Acceptance:** 60.0%

**Tags:** `Array`, `Two Pointers`, `Greedy`

## Problem

You are given an integer array height of length n. There are n vertical lines drawn such that the two endpoints of the ith line are (i, 0) and (i, height[i]).

Find two lines that together with the x-axis form a container, such that the container contains the most water.

Return the maximum amount of water a container can store.

Notice that you may not slant the container.

&nbsp;
Example 1:

Input: height = [1,8,6,2,5,4,8,3,7]
Output: 49
Explanation: The above vertical lines are represented by array [1,8,6,2,5,4,8,3,7]. In this case, the max area of water (blue section) the container can contain is 49.

Example 2:

Input: height = [1,1]
Output: 1

&nbsp;
Constraints:

	n == height.length
	2 <= n <= 105
	0 <= height[i] <= 104

## My Submission

- Runtime: 66 ms
- Memory: 29.4 MB

## Similar Problems

- [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) — Hard
- [Maximum Tastiness of Candy Basket](https://leetcode.com/problems/maximum-tastiness-of-candy-basket/) — Medium
- [House Robber IV](https://leetcode.com/problems/house-robber-iv/) — Medium
