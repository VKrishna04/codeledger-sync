# Edit Distance

**Difficulty:** Medium  |  **Acceptance:** 60.5%

**Tags:** `String`, `Dynamic Programming`

## Problem

Given two strings word1 and word2, return the minimum number of operations required to convert word1 to word2.

You have the following three operations permitted on a word:

	Insert a character
	Delete a character
	Replace a character

&nbsp;
Example 1:

Input: word1 = "horse", word2 = "ros"
Output: 3
Explanation: 
horse -> rorse (replace 'h' with 'r')
rorse -> rose (remove 'r')
rose -> ros (remove 'e')

Example 2:

Input: word1 = "intention", word2 = "execution"
Output: 5
Explanation: 
intention -> inention (remove 't')
inention -> enention (replace 'i' with 'e')
enention -> exention (replace 'n' with 'x')
exention -> exection (replace 'n' with 'c')
exection -> execution (insert 'u')

&nbsp;
Constraints:

	0 <= word1.length, word2.length <= 500
	word1 and word2 consist of lowercase English letters.

## My Submission

- Runtime: 44 ms
- Memory: 22.7 MB

## Similar Problems

- [Delete Operation for Two Strings](https://leetcode.com/problems/delete-operation-for-two-strings/) — Medium
- [Minimum ASCII Delete Sum for Two Strings](https://leetcode.com/problems/minimum-ascii-delete-sum-for-two-strings/) — Medium
- [Uncrossed Lines](https://leetcode.com/problems/uncrossed-lines/) — Medium
- [Minimum White Tiles After Covering With Carpets](https://leetcode.com/problems/minimum-white-tiles-after-covering-with-carpets/) — Hard
- [Longest Palindrome After Substring Concatenation II](https://leetcode.com/problems/longest-palindrome-after-substring-concatenation-ii/) — Hard
