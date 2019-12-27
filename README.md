# Machine_coding FLIPKART
## Error Finder Application Problem Statement



Q)Given a binary tree as a sequence of (parent, child) tuples: (A B)(A C)(B G)(C H)(E F)(B D)(C E) Write a program to find following errors in the tree:



- E1: More than 2 children
- E2: Duplicate Tuples
- E3: Cycle present
- E4: Multiple roots
- E5: Multiple parents



Input is a expression containing parent child relations. output is Error codes or success.
Sample test cases
- Input: (A B)(A C)(B G)(C H)(E F)(B D)(C E) Output: Success
- Input: (A B)(A C)(A D) Output: E1
- Input: (A B)(A B) Output: E2
- Input: (A B)(B C)(C A) Output: E3
- Input: (A B)(C D) Output: E4
- Input: (A B)(B C)(A C) Output: E5

```diff
+ Solution: Code can be found in ErrorFinderApplication.zip, written in java.
```
## Design a Ride Matching application 

Find all the eligible drivers for a rider cosidering below conditions. 

1. The average rating of the driver should be greater than the customer average rating.

2. If the customer had given the driver a 1 star rating earlier then this driver is not to be considered vice versa.
  (In average rating calculation this driver's rides are not cosidered for a rider.)

3. If there are no drivers found, print the ones for which the customer had rode earlier.

- Bonus: Show online drivers at any time. 

```diff
+ Solution: Code can be found in DriverAndRiderApplication.zip, written in java.
```

## Design an Ecommerce storage system

1. You can add a product -> addProduct(“p1”)
2. A user can purchase a product -> purchase(“u1″,”p1”)
3. A user can return a product -> returnProduct(“u1″,”p1”)
4. A user can be blacklisted and all of his purchases will be marked null -> blackListUser(“u1”)
5. Display the best selling product -> bestSelling()

- Best selling product will be the one which have been bought by most number of unique users.
- Bonus: Display the best selling products for each category.

```diff
+ Solution: Code can be found in OrderBookingSystem.zip, written in java.
```

## Implement a Text Line Editor which supports the following operations:

- insert a line at a given line number
- delete the specific set of lines
- Copy specific set of lines
- Paste the copied lines at given index
- Print the entire content

`Bonus`

1. Undo command
2. Redo command
