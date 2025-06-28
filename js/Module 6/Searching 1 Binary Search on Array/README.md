**Q1. Sorted Insert Position**

Problem Description

You are given a sorted array A of size N and a target value B.
Your task is to find the index (0-based indexing) of the target value in the array.

If the target value is present, return its index.
If the target value is not found, return the index of least element greater than equal to B.
If the target value is not found and least number greater than equal to target is also not present, return the length of array (i.e. the position where target can be placed)
Your solution should have a time complexity of O(log(N)).


Problem Constraints

1 <= N <= 105
1 <= A[i] <= 105
1 <= B <= 105



Input Format

The first argument is an integer array A of size N.
The second argument is an integer B.



Output Format

Return an integer denoting the index of target value.



Example Input

Input 1:

A = [1, 3, 5, 6]
B = 5 
Input 2:

A = [1, 4, 9]
B = 3


Example Output

Output 1:

2 
Output 2:

1


Example Explanation

Explanation 1:

The target value is present at index 2. 
Explanation 2:

The target value should be inserted at index 1.


**Q2. Search for a Range**

Problem Description

Given a sorted array of integers A (0-indexed) of size N, find the left most and the right most index of a given integer B in the array A.

Return an array of size 2, such that 
          First element = Left most index of B in A
          Second element = Right most index of B in A.
If B is not found in A, return [-1, -1].

Note : Note: The time complexity of your algorithm must be O(log n)..


Problem Constraints

1 <= N <= 106
1 <= A[i], B <= 109


Input Format

The first argument given is the integer array A.
The second argument given is the integer B.


Output Format

Return the left most and right most index (0-based) of B in A as a 2-element array. If B is not found in A, return [-1, -1].


Example Input

Input 1:

 A = [5, 7, 7, 8, 8, 10]
 B = 8
Input 2:

 A = [5, 17, 100, 111]
 B = 3


Example Output

Output 1:

 [3, 4]
Output 2:

 [-1, -1]


Example Explanation

Explanation 1:

 The first occurrence of 8 in A is at index 3.
 The last occurrence of 8 in A is at index 4.
 ans = [3, 4]
Explanation 2:

 There is no occurrence of 3 in the array.

**Q3. Find a peak element**
Problem Description

Given an array of integers A, find and return the peak element in it.
An array element is considered a peak if it is not smaller than its neighbors. For corner elements, we need to consider only one neighbor.

NOTE:

It is guaranteed that the array contains only a single peak element.
Users are expected to solve this in O(log(N)) time. The array may contain duplicate elements.


Problem Constraints

1 <= |A| <= 100000

1 <= A[i] <= 109



Input Format

The only argument given is the integer array A.



Output Format

Return the peak element.



Example Input

Input 1:

A = [1, 2, 3, 4, 5]
Input 2:

A = [5, 17, 100, 11]




Example Output

Output 1:


 5
Output 2:

 100


Example Explanation

Explanation 1:

 5 is the peak.
Explanation 2:

 100 is the peak.

**Q4. Single Element in Sorted Array**

Problem Description

Given a sorted array of integers A where every element appears twice except for one element which appears once, find and return this single element that appears only once.

Elements which are appearing twice are adjacent to each other.

NOTE: Users are expected to solve this in O(log(N)) time.



Problem Constraints

1 <= |A| <= 100000

1 <= A[i] <= 10^9



Input Format

The only argument given is the integer array A.



Output Format

Return the single element that appears only once.



Example Input

Input 1:

A = [1, 1, 7]
Input 2:

A = [2, 3, 3]


Example Output

Output 1:

 7
Output 2:

 2


Example Explanation

Explanation 1:

 7 appears once
Explanation 2:

 2 appears once


**Q5. Matrix Search**
Problem Description

Given a matrix of integers A of size N x M and an integer B. Write an efficient algorithm that searches for integer B in matrix A.

This matrix A has the following properties:

Integers in each row are sorted from left to right.
The first integer of each row is greater than or equal to the last integer of the previous row.
Return 1 if B is present in A, else return 0.

NOTE: Rows are numbered from top to bottom, and columns are from left to right.



Problem Constraints

1 <= N, M <= 1000
1 <= A[i][j], B <= 106



Input Format

The first argument given is the integer matrix A.
The second argument given is the integer B.



Output Format

Return 1 if B is present in A else, return 0.



Example Input

Input 1:

A = [ 
      [1,   3,  5,  7]
      [10, 11, 16, 20]
      [23, 30, 34, 50]  
    ]
B = 3
Input 2:

A = [   
      [5, 17, 100, 111]
      [119, 120, 127, 131]    
    ]
B = 3


Example Output

Output 1:

1
Output 2:

0


Example Explanation

Explanation 1:

 3 is present in the matrix at A[0][1] position so return 1.
Explanation 2:

 3 is not present in the matrix so return 0.

**Q1. Minimum Difference**

Problem Description

You are given a 2-D matrix C of size A × B.
You need to build a new 1-D array of size A by taking one element from each row of the 2-D matrix in such a way that the cost of the newly built array is minimized.

The cost of an array is the minimum possible value of the absolute difference between any two adjacent elements of the array.

So if the newly built array is X, the element picked from row 1 will become X[1], element picked from row 2 will become X[2], and so on.

Determine the minimum cost of the newly built array.



Problem Constraints

2 <= A <= 1000
2 <= B <= 1000
1 <= C[i][j] <= 106



Input Format

The first argument is an integer A denoting number of rows in the 2-D array.
The second argument is an integer B denoting number of columns in the 2-D array.
The third argument is a 2-D array C of size A x B.



Output Format

Return an integer denoting the minimum cost of the newly build array.



Example Input

Input 1:

 A = 2
 B = 2
 C = [ [8, 4]
      [6, 8] ]
Input 2:

 A = 3
 B = 2
 C = [ [7, 3]
       [2, 1]
       [4, 9] ]


Example Output

Output 1:

 0
Output 2:

 1


Example Explanation

Explanation 1:

 Newly build array : [8, 8]. The minimum cost will be 0 since the absolute difference will be 0(8-8).
Explanation 2:

 Newly build array : [3, 2, 4]. The minimum cost will be 1 since the minimum absolute difference will be 1(3 - 2).

**Q2. Maximum height of staircase**

Problem Description

Given an integer A representing the number of square blocks. The height of each square block is 1. The task is to create a staircase of max-height using these blocks.

The first stair would require only one block, and the second stair would require two blocks, and so on.

Find and return the maximum height of the staircase.



Problem Constraints

0 <= A <= 109


Input Format

The only argument given is integer A.



Output Format

Return the maximum height of the staircase using these blocks.



Example Input

Input 1:

 A = 10
Input 2:

 A = 20


Example Output

Output 1:

 4
Output 2:

 5


Example Explanation

Explanation 1:

 The stairs formed will have height 1, 2, 3, 4.
Explanation 2:

 The stairs formed will have height 1, 2, 3, 4, 5.
