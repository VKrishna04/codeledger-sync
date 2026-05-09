# Koko Eating Bananas

**Difficulty:** Medium  |  **Acceptance:** 50.0%

**Tags:** `Array`, `Binary Search`

## Problem

Koko loves to eat bananas. There are n piles of bananas, the ith pile has piles[i] bananas. The guards have gone and will come back in h hours.

Koko can decide her bananas-per-hour eating speed of k. Each hour, she chooses some pile of bananas and eats k bananas from that pile. If the pile has less than k bananas, she eats all of them instead and will not eat any more bananas during this hour.

Koko likes to eat slowly but still wants to finish eating all the bananas before the guards return.

Return the minimum integer k such that she can eat all the bananas within h hours.

&nbsp;
Example 1:

Input: piles = [3,6,7,11], h = 8
Output: 4

Example 2:

Input: piles = [30,11,23,4,20], h = 5
Output: 30

Example 3:

Input: piles = [30,11,23,4,20], h = 6
Output: 23

&nbsp;
Constraints:

	1 <= piles.length <= 104
	piles.length <= h <= 109
	1 <= piles[i] <= 109

## My Submission

- Runtime: 155 ms
- Memory: 18.9 MB

## Similar Problems

- [Maximum Candies Allocated to K Children](https://leetcode.com/problems/maximum-candies-allocated-to-k-children/) — Medium
- [Minimized Maximum of Products Distributed to Any Store](https://leetcode.com/problems/minimized-maximum-of-products-distributed-to-any-store/) — Medium
- [Frog Jump II](https://leetcode.com/problems/frog-jump-ii/) — Medium
- [Minimum Time to Repair Cars](https://leetcode.com/problems/minimum-time-to-repair-cars/) — Medium
