# Create Hello World Function

**Difficulty:** Easy  |  **Acceptance:** 81.9%

**Tags:** —

## Problem

Write a function&nbsp;createHelloWorld.&nbsp;It should return a new function that always returns&nbsp;"Hello World".
&nbsp;
Example 1:

Input: args = []
Output: "Hello World"
Explanation:
const f = createHelloWorld();
f(); // "Hello World"

The function returned by createHelloWorld should always return "Hello World".

Example 2:

Input: args = [{},null,42]
Output: "Hello World"
Explanation:
const f = createHelloWorld();
f({}, null, 42); // "Hello World"

Any arguments could be passed to the function but it should still always return "Hello World".

&nbsp;
Constraints:

	0 <= args.length <= 10

## My Submission

- Runtime: 55 ms
- Memory: 49 MB
