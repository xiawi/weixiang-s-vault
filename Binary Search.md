---
tags:
  - note
  - "#algorithm"
up: "[[Grokking Algorithms]]"
date: 2025-01-20
---
A search algorithm that takes inputs in the form of
1. A sorted array.
2. A target element.
and outputs the target element's index.

General Procedure:
1. Obtain middle element of the list.
2. Compare element with target.
3. If element is lower than target, consider the later half of the array, otherwise consider the higher. If element is target, return index.
4. If we've checked the entire list and still have yet to find anything, we return None.