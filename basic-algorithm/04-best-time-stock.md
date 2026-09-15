## Problem: Best Time to Buy and Sell Stock (Easy)

**Link:** https://leetcode.com/problems/best-time-to-buy-and-sell-stock/

### Approach

I keep track of the minimum price seen so far.
For every price, I calculate the possible profit and update the maximum profit.

### Complexity

- Time: O(n)
- Space: O(1)

### Notes

If prices continuously decrease, the answer is 0.