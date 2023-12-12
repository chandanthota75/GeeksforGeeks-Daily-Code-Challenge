# Subarray with 0 Sum

## Problem Statement

Given an array of integers. Find if there is a subarray (of size at least one) with a 0 sum. Return true/false depending on whether there is a subarray present with a 0 sum.

### Example 1:

**Input:**
n = 5
arr = [4, 2, -3, 1, 6]

**Output:**
Yes


**Explanation:**
`[2, -3, 1]` is the subarray with sum 0.

### Example 2:

**Input:**
n = 5
arr = [4, 2, 0, 1, 6]

**Output:**
Yes


**Explanation:**
`0` is one of the elements in the array, so there exists a subarray with sum 0.

## Your Task

You only need to complete the function `subArrayExists()` that takes an array and `n` as parameters and returns `true` or `false`.

**Expected Time Complexity:** O(n)

**Expected Auxiliary Space:** O(n)

## Constraints

- 1 ≤ n ≤ 104
- -105 ≤ a[i] ≤ 105
