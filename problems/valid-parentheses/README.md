# Valid Parentheses

**Difficulty:** Easy  |  **Acceptance:** 44.1%

**Tags:** `String`, `Stack`

## Problem

Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.

An input string is valid if:

	Open brackets must be closed by the same type of brackets.
	Open brackets must be closed in the correct order.
	Every close bracket has a corresponding open bracket of the same type.

&nbsp;
Example 1:

Input: s = "()"

Output: true

Example 2:

Input: s = "()[]{}"

Output: true

Example 3:

Input: s = "(]"

Output: false

Example 4:

Input: s = "([])"

Output: true

Example 5:

Input: s = "([)]"

Output: false

&nbsp;
Constraints:

	1 <= s.length <= 104
	s consists of parentheses only '()[]{}'.

## My Submission

- Runtime: 4 ms
- Memory: 16.6 MB

## Similar Problems

- [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) — Medium
- [Longest Valid Parentheses](https://leetcode.com/problems/longest-valid-parentheses/) — Hard
- [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) — Hard
- [Check If Word Is Valid After Substitutions](https://leetcode.com/problems/check-if-word-is-valid-after-substitutions/) — Medium
- [Check if a Parentheses String Can Be Valid](https://leetcode.com/problems/check-if-a-parentheses-string-can-be-valid/) — Medium
