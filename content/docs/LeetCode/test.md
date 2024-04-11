---
title: 402. Remove K Digits
type: docs
prev: docs/folder/
---

### Given two sequences of digit of the same length, it is the leftmost distinct digits that determine the superior of the two numbers. 
### For example, A = 1axxx, B = 1bxxx, if the digits a > b , then A > B
### With this insight, the first intuition we got for our problem is that we should iterate from the left to right, when removing the digits.
### For exaple we have a num 425, if we are asked to remove just one digit, then from left to right, we have canditate 4, 2, and 5. 