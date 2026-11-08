## Intuition
Since the array is sorted, duplicate elements are always adjacent. We can use two pointers to keep track of unique elements and place them at the beginning of the array.

## Approach
1. Initialize k = 1 because the first element is always unique.
2. Traverse the array starting from index 1.
3. Compare nums[i] with nums[k-1].
4. If both elements are different, we found a new unique element.
5. Place the unique element at nums[k] and increment k.
6. Return k, representing the total number of unique elements.

## Complexity Analysis

- Time Complexity: O(n) - We traverse the array once.
- Space Complexity: O(1) - In-place modification without extra space.

## Topics
- Array
- Two Pointers
- In-place Algorithm
