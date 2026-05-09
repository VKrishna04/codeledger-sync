# Shortest Common Supersequence 

**Difficulty:** Hard  |  **Acceptance:** 61.9%

**Tags:** `String`, `Dynamic Programming`

## Problem

Given two strings str1 and str2, return the shortest string that has both str1 and str2 as subsequences. If there are multiple valid strings, return any of them.

A string s is a subsequence of string t if deleting some number of characters from t (possibly 0) results in the string s.

&nbsp;
Example 1:

Input: str1 = "abac", str2 = "cab"
Output: "cabac"
Explanation: 
str1 = "abac" is a subsequence of "cabac" because we can delete the first "c".
str2 = "cab" is a subsequence of "cabac" because we can delete the last "ac".
The answer provided is the shortest such string that satisfies these properties.

Example 2:

Input: str1 = "aaaaaaaa", str2 = "aaaaaaaa"
Output: "aaaaaaaa"

&nbsp;
Constraints:

	1 <= str1.length, str2.length <= 1000
	str1 and str2 consist of lowercase English letters.

## My Submission

- Runtime: 342 ms
- Memory: 44.4 MB

## Similar Problems

- [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) — Medium
- [Shortest String That Contains Three Strings](https://leetcode.com/problems/shortest-string-that-contains-three-strings/) — Medium
