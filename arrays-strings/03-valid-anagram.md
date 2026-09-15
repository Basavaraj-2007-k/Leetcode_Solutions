## Problem: Valid Anagram (Easy)

**Link:** https://leetcode.com/problems/valid-anagram/

### Approach

I used an array of 26 counters to store the frequency of each lowercase letter.
The strings are anagrams if all frequency values become zero.

### Complexity

- Time: O(n)
- Space: O(1)

### Notes

The strings must have the same length before comparing frequencies.