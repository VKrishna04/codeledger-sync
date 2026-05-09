# Greatest Common Divisor of Strings

**Difficulty:** Easy  |  **Acceptance:** 53.7%

**Tags:** `Math`, `String`

## Problem

For two strings s and t, we say "t divides s" if and only if s = t + t + t + ... + t + t (i.e., t is concatenated with itself one or more times).

Given two strings str1 and str2, return the largest string x such that x divides both str1 and str2.

&nbsp;
Example 1:

Input: str1 = "ABCABC", str2 = "ABC"

Output: "ABC"

Example 2:

Input: str1 = "ABABAB", str2 = "ABAB"

Output: "AB"

Example 3:

Input: str1 = "LEET", str2 = "CODE"

Output: ""

Example 4:

Input: str1 = "AAAAAB", str2 = "AAA"

Output: ""​​​​​​​

&nbsp;
Constraints:

	1 <= str1.length, str2.length <= 1000
	str1 and str2 consist of English uppercase letters.

## My Submission

- Runtime: 0 ms
- Memory: 19.3 MB

## Similar Problems

- [Find Greatest Common Divisor of Array](https://leetcode.com/problems/find-greatest-common-divisor-of-array/) — Easy
- [Smallest Even Multiple](https://leetcode.com/problems/smallest-even-multiple/) — Easy
- [Find the Maximum Factor Score of Array](https://leetcode.com/problems/find-the-maximum-factor-score-of-array/) — Medium
