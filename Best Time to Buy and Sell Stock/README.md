# Intuition

We need to find the lowest stock price and the maximum profit by selling at a later day.

# Approach

- Keep track of the minimum price seen so far.
- Calculate profit by subtracting the minimum price from the current price.
- Update the maximum profit if the current profit is higher.
- Return the maximum profit.

# Complexity

- Time complexity: O(n) — We iterate through the array once.
- Space complexity: O(1) — We use only two variables.
