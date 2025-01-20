---
tags:
  - book
author(s): Aditya Y. Bhargava
date started: 2025-01-20
date completed:
---
```table-of-contents
```
# Introduction
> [!info] 
> $log$ refers to $log_{2}$
## [[Binary Search]]
### A better way to search
#### Exercises
1. **Suppose you have a sorted list of 128 names, and you’re searching through it using binary search. What’s the maximum number of steps it would take?**
   It would take a maximum of $log_{2}128 = 7$ steps.
2. **Suppose you double the size of the list. What’s the maximum number of steps now?**
   Eight, since binary search effectively halves the search space each loop-through.
## Big O notation
### Some common Big O run times
#### Exercises
3. O(log(n))
4. O(n)
5. O(n)
6. O(n)
# Selection 
## [[How computer memory works]]
## Arrays and linked lists
- [[Arrays]]
### [[Linked Lists]]
### Arrays
- Linked lists are great if we're reading our data in sequence, but it's utter shit when it comes to reading data in a more sporadic manner (reading the last element or the 6th element or something). In these cases, arrays are a more suitable data structure.
#### Exercises
1. List
### Inserting into the middle of a list.
- Arrays are dogshit if we're going to be inserting elements into the middle of our data structure. We'll need to shift everything on the right of the array one address to the left before slotting it in. And if we have less space than we need, we'll need to move the whole array somewhere else. Linked lists do this better, we can find an empty address and slot our item in and adjust the pointer of an existing item.
### Deletions
- Same with insertions
#### Exercises
2. Linked List
3. Array
4. O(n) insertions. Slow insertions because elements may need to shift in order to make room for new ones to keep sorting. 
5. Insertions: Faster than an array
   Searching: Faster than a linked list, slower than an array.
## [[Selection Sort]]
# Recursion
## Base case and recursive case
- When writing a recursive function, it is important that it has both parts: the recursive case and the base case.
- The recursive case is when the function calls itself.
- The base case is when the function stops calling itself; it completes.
## The stack
