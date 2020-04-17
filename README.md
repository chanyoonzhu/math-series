# Challenge Summary
Write functions to produce Fibonacci, Lucas series, and sum series starting with any arbitrary sequences.

## Challenge Description
The Fibonacci Series is a numeric series starting with the integers 0 and 1. In this series, the next integer is determined by summing the previous two. This gives us:

0, 1, 1, 2, 3, 5, 8, 13, ...

The Lucas Numbers are a related series of integers that start with the values 2 and 1 rather than 0 and 1. The resulting series looks like this:

2, 1, 3, 4, 7, 11, 18, 29, ...

Both the fibonacci series and the lucas numbers are based on an identical formula. Add a third function called sum_series with one required parameter and two optional parameters. Calling this function with no optional parameters will produce numbers from the fibonacci series. Calling it with the optional arguments 2 and 1 will produce values from the lucas numbers. Other values for the optional parameters will produce other series. 

## Approach & Efficiency
Dynamic programming (a list to backtrack series that is already computed)
Time complexity: O(n)
Space complexity: O(n)

## Solution
series.py
