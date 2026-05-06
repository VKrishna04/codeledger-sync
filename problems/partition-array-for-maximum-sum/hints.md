# Hints — Partition Array for Maximum Sum

### Hint 1

Think dynamic programming:  dp[i] will be the answer for array A[0], ..., A[i-1].

### Hint 2

For j = 1 .. k that keeps everything in bounds, dp[i] is the maximum of dp[i-j] + max(A[i-1], ..., A[i-j]) * j .
