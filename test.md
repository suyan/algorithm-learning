## 1. Question
Given an array of integers, find two numbers such that they add up to a specific target number.

The function `twoSum` should return indices of the two numbers such that they add up to the target, where index1 must be less than index2. Please note that your returned answers (both index1 and index2) are NOT zero-based.

### Example
number = `[2, 7, 11, 15]`, target = `9`
return `[1, 2]`

### Note 
You may assume that each input would have exactly one solution

### Challenge
Either of the following solutions are acceptable:
- O(n) Space, O(nlogn) Time
- O(n) Space, O(n) Time

## 2. Analysis

1. Brute-force approach need $$O(n^2)$$
2. Sort first $$O(nlgn)$$ and use two pointer to find target $$O(n)$$
3. Use a hashmap that number is key and index is value, traverse this array and save every pair. Traverse again to find if `target - value` in hashmap.



