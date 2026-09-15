## Problem: Valid Parentheses (Easy)

**Link:** https://leetcode.com/problems/valid-parentheses/

### Approach

I used a stack to store opening brackets.
Whenever a closing bracket appears, it is matched with the most recent opening bracket.

### Complexity

- Time: O(n)
- Space: O(n)

### Notes

An empty stack before processing a closing bracket means the string is invalid.