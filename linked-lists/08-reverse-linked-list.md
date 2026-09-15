## Problem: Reverse Linked List (Easy)

**Link:** https://leetcode.com/problems/reverse-linked-list/

### Approach

I use three pointers: previous, current, and next.
Each node's next pointer is changed to point to the previous node.

### Complexity

- Time: O(n)
- Space: O(1)

### Notes

The previous pointer becomes the new head after all nodes are processed.