# First Bad Version

**Difficulty:** Easy  |  **Acceptance:** 47.1%

**Tags:** `Binary Search`, `Interactive`

## Problem

You are a product manager and currently leading a team to develop a new product. Unfortunately, the latest version of your product fails the quality check. Since each version is developed based on the previous version, all the versions after a bad version are also bad.

Suppose you have n versions [1, 2, ..., n] and you want to find out the first bad one, which causes all the following ones to be bad.

You are given an API bool isBadVersion(version) which returns whether version is bad. Implement a function to find the first bad version. You should minimize the number of calls to the API.

&nbsp;
Example 1:

Input: n = 5, bad = 4
Output: 4
Explanation:
call isBadVersion(3) -> false
call isBadVersion(5)&nbsp;-> true
call isBadVersion(4)&nbsp;-> true
Then 4 is the first bad version.

Example 2:

Input: n = 1, bad = 1
Output: 1

&nbsp;
Constraints:

	1 <= bad <= n <= 231 - 1

## My Submission

- Runtime: 32 ms
- Memory: 16.6 MB

## Similar Problems

- [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) — Medium
- [Search Insert Position](https://leetcode.com/problems/search-insert-position/) — Easy
- [Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower/) — Easy
