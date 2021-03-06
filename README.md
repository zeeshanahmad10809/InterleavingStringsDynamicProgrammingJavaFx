# Interleaving Strings Dynamic Programming JavaFx

### What is string interleaving?
Given three strings s1, s2 and s3. Write a function that checks whether s3 is an interleaving of s1 and s2. s3 is said to be interleaving s1 and s2, if it contains all characters of s1 and s2 and order of all characters in individual strings is preserved.

### What is dynamic programming?
Dynamic Programming is mainly an optimization over plain recursion. Wherever we see a recursive solution that has repeated calls for same inputs, we can optimize it using Dynamic Programming. The idea is to simply store the results of subproblems, so that we do not have to re-compute them when needed later. This simple optimization reduces time complexities from exponential to polynomial.

### How it works?
- We just need to input strings s1, s2 and s3.
- Create Table.
- Fill Table.
- If bottom-right cell of table is True then strings are interleaving otherwise if False then strings are not interleaving.

### Requirements
- javac 1.8.0_121

### Recommended IDE
- IntelliJ IDEA

### User Interface
![alt text](https://github.com/zeeshanahmad10809/Interleaving-Strings-Dynamic-Programming-JavaFx-/blob/master/.interleaving_strings.png)
