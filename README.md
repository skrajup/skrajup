# ✅ Practice Plan

## 📌 Table of Contents
- [Week 1: Python Refresher, Arrays & Strings](#%EF%B8%8F-week-1-python-refresher-arrays--strings)
- [Week 2: Stacks, Queues & Hashmaps](#%EF%B8%8F-week-2-stacks-queues--hashmaps)
- [Week 3: Linked Lists & Recursion](#%EF%B8%8F-week-3-linked-lists--recursion)
- [Week 4: Trees & Binary Search](#%EF%B8%8F-week-4-trees--binary-search)
- [Week 5: Graphs & Backtracking](#%EF%B8%8F-week-5-graphs--backtracking)
- [Week 6: Dynamic Programming (DP)](#%EF%B8%8F-week-6-dynamic-programming-dp)


## 🗓️ Week 1: Python Refresher, Arrays & Strings
### 📚 Concepts
- [ ] Review Python basics (lists, sets, dicts, loops, functions)

### 💻 Problems
- [ ] Solve `Two Sum`
- [ ] Solve `Best Time to Buy and Sell Stock`
- [ ] Solve `Contains Duplicate`
- [ ] Solve `Valid Anagram`
- [ ] Solve `Valid Palindrome`
- [ ] Solve `Reverse String`
- [ ] Solve `Merge Sorted Array`
- [ ] Solve `Move Zeroes`
- [ ] Solve `Longest Common Prefix`
- [ ] Solve `Longest Substring Without Repeating Characters`

### 🔁 Revision Focus
- [ ] Revise list & string methods: `.append()`, slicing, `.join()`
- [ ] Understand two-pointer & sliding window patterns
- [ ] Practice using hash sets/maps to detect duplicates
- [ ] Reflect on edge cases: empty strings, single elements
- [ ] Re-attempt 2 previously solved problems cold (no notes)

---

## 🗓️ Week 2: Stacks, Queues & Hashmaps
### 📚 Concepts
- [ ] Learn about Stack, Queue, Deque in Python
- [ ] Practice `collections.deque`, `defaultdict`, `Counter`

### 💻 Problems
- [ ] Solve `Valid Parentheses`
- [ ] Solve `Min Stack`
- [ ] Solve `Implement Queue using Stacks`
- [ ] Solve `Implement Stack using Queues`
- [ ] Solve `First Unique Character in a String`
- [ ] Solve `Group Anagrams`
- [ ] Solve `Top K Frequent Elements`
- [ ] Solve `Intersection of Two Arrays`
- [ ] Solve `Design Circular Queue`

### 🔁 Revision Focus
- [ ] Understand stack vs queue use cases and real-world applications
- [ ] Know Python implementations (`list`, `deque`)
- [ ] Learn when to use `Counter`, `defaultdict`, `dict`
- [ ] Review stack state evolution during problems
- [ ] Re-attempt 1 hashmap + 1 queue-based problem cold

---

## 🗓️ Week 3: Linked Lists & Recursion
### 📚 Concepts
- [ ] Visualize pointer movements
- [ ] Practice recursion step-by-step

### 💻 Problems
- [ ] Solve `Reverse Linked List`
- [ ] Solve `Merge Two Sorted Lists`
- [ ] Solve `Remove Nth Node From End of List`
- [ ] Solve `Linked List Cycle`
- [ ] Solve `Palindrome Linked List`
- [ ] Solve `Intersection of Two Linked Lists`
- [ ] Solve `Add Two Numbers`
- [ ] Solve `Fibonacci (recursion + memoization)`
- [ ] Solve `Factorial (recursive)`

### 🔁 Revision Focus
- [ ] Practice dry-running recursive functions
- [ ] Revisit base case + return logic in recursion
- [ ] Use diagrams to understand `slow`/`fast`/`prev` pointers
- [ ] Re-implement 1 recursive + 1 pointer-based LL problem cold

---

## 🗓️ Week 4: Trees & Binary Search
### 📚 Concepts
- [ ] Understand tree vs BST
- [ ] Learn traversal types (pre/in/post/level)
- [ ] Master binary search logic

### 💻 Problems
- [ ] Solve `Maximum Depth of Binary Tree`
- [ ] Solve `Invert Binary Tree`
- [ ] Solve `Same Tree`
- [ ] Solve `Diameter of Binary Tree`
- [ ] Solve `Symmetric Tree`
- [ ] Solve `Binary Tree Level Order Traversal`
- [ ] Solve `Validate Binary Search Tree`
- [ ] Solve `Binary Search`
- [ ] Solve `Search Insert Position`
- [ ] Solve `Find First and Last Position of Element in Sorted Array`

### 🔁 Revision Focus
- [ ] Review traversal implementations (recursive + iterative)
- [ ] Draw tree diagrams to simulate traversal paths
- [ ] Trace `low`, `high`, `mid` changes during binary search
- [ ] Re-attempt 1 tree + 1 binary search problem cold

---

## 🗓️ Week 5: Graphs & Backtracking
### 📚 Concepts
- [ ] Understand BFS vs DFS
- [ ] Build graphs using adjacency lists
- [ ] Practice backtracking (choose → explore → unchoose)

### 💻 Problems
- [ ] Solve `Number of Islands`
- [ ] Solve `Flood Fill`
- [ ] Solve `Clone Graph`
- [ ] Solve `Course Schedule`
- [ ] Solve `Pacific Atlantic Water Flow`
- [ ] Solve `Letter Combinations of a Phone Number`
- [ ] Solve `Subsets`
- [ ] Solve `Permutations`
- [ ] Solve `Word Search`

### 🔁 Revision Focus
- [ ] Trace BFS and DFS step-by-step on paper
- [ ] Review visited set logic to avoid infinite loops
- [ ] Practice the backtracking template:
  ```python
  def backtrack(path):
      if is_solution(path):
          res.append(path)
          return
      for choice in choices:
          make_choice()
          backtrack(path)
          undo_choice()
- [ ] Re-attempt 1 DFS + 1 backtracking problem cold

---

## 🗓️ Week 6: Dynamic Programming (DP)
### 📚 Concepts
- [ ] Learn memoization vs tabulation
- [ ] Identify overlapping subproblems & optimal substructure

### 💻 Problems
- [ ] Solve `Climbing Stairs`
- [ ] Solve `House Robber`
- [ ] Solve `House Robber II`
- [ ] Solve `Word Break`
- [ ] Solve `Coin Change`
- [ ] Solve `Maximum Subarray (Kadane’s Algorithm)`
- [ ] Solve `Unique Paths`
- [ ] Solve `Longest Palindromic Substring`
- [ ] Solve `Longest Common Subsequence`
- [ ] Solve `Partition Equal Subset Sum`

### 🔁 Revision Focus
- [ ] Practice defining DP state (parameters)
- [ ] Convert recursive → memoized → tabulated
- [ ] Learn common DP categories: sequences, decisions, subsets
- [ ] Draw the DP table for 1–2 problems manually
- [ ] Re-attempt 2 previously solved DP problems cold
