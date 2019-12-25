# Machine_coding
# Error Finder Application Problem Statement 



Q)Given a binary tree as a sequence of (parent, child) tuples: (A B)(A C)(B G)(C H)(E F)(B D)(C E) Write a program to find following errors in the tree:



E1: More than 2 children
E2: Duplicate Tuples
E3: Cycle present
E4: Multiple roots
E5: Multiple parents



Input is a expression containing parent child relations. output is Error codes or success.
Sample test cases
Input: (A B)(A C)(B G)(C H)(E F)(B D)(C E) Output: Success
Input: (A B)(A C)(A D) Output: E1
Input: (A B)(A B) Output: E2
Input: (A B)(B C)(C A) Output: E3
Input: (A B)(C D) Output: E4
Input: (A B)(B C)(A C) Output: E5

