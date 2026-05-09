# Merge Strings Alternately

**Difficulty:** Easy  |  **Acceptance:** 82.1%

**Tags:** `Two Pointers`, `String`

## Problem

You are given two strings word1 and word2. Merge the strings by adding letters in alternating order, starting with word1. If a string is longer than the other, append the additional letters onto the end of the merged string.

Return the merged string.

&nbsp;
Example 1:


Input: word1 = "abc", word2 = "pqr"
Output: "apbqcr"
Explanation:&nbsp;The merged string will be merged as so:
word1:  a   b   c
word2:    p   q   r
merged: a p b q c r


Example 2:


Input: word1 = "ab", word2 = "pqrs"
Output: "apbqrs"
Explanation:&nbsp;Notice that as word2 is longer, "rs" is appended to the end.
word1:  a   b 
word2:    p   q   r   s
merged: a p b q   r   s


Example 3:


Input: word1 = "abcd", word2 = "pq"
Output: "apbqcd"
Explanation:&nbsp;Notice that as word1 is longer, "cd" is appended to the end.
word1:  a   b   c   d
word2:    p   q 
merged: a p b q c   d


&nbsp;
Constraints:


	1 <= word1.length, word2.length <= 100
	word1 and word2 consist of lowercase English letters.

## My Submission

- Runtime: 1 ms
- Memory: 41.9 MB

## Similar Problems

- [Minimum Additions to Make Valid String](https://leetcode.com/problems/minimum-additions-to-make-valid-string/) — Medium
