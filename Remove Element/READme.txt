# Intuition
We need to remove all occurrences of val from the array without creating a new array. We can use two pointers to keep track of valid elements and their positions.

# Approach
1. Initialize k = 0 to track the position of the next valid element.

2. Loop through the array using i.

3. If nums[i] != val, copy nums[i] to nums[k] and increment k.

4. Skip elements equal to val.

5. Return k, which represents the number of elements remaining.

# Complexity
- Time complexity: O(n) - We iterate through the array once.

- Space complexity: O(1) - We use only a constant amount of extra space.
