**Arrays - Prefix Sum**

Q1. Prefix Sum Formula

prefSum[i] = prefSum[i - 1] + A[i]

Time Complexity of Prefix Sum
O(N)

**Example : Range Sum Query**

Problem Description

You are given an integer array A of length N.
You are also given a 2D integer array B with dimensions M x 2, where each row denotes a [L, R] query.
For each query, you have to find the sum of all elements from L to R indices in A (0 - indexed).
More formally, find A[L] + A[L + 1] + A[L + 2] +... + A[R - 1] + A[R] for each query.

Problem Constraints

1 <= N, M <= 105
1 <= A[i] <= 109
0 <= L <= R < N

Input Format

The first argument is the integer array A.
The second argument is the 2D integer array B.

Output Format

Return an integer array of length M where ith element is the answer for ith query in B.

Example Input

Input 1:

A = [1, 2, 3, 4, 5]
B = [[0, 3], [1, 2]]

Input 2:

A = [2, 2, 2]
B = [[0, 0], [1, 2]]

Example Output

Output 1:

[10, 5]

Output 2:

[2, 4]


**Example Special Index**

Problem Description

Given an array, arr[] of size N, the task is to find the count of array indices such that removing an element from these indices makes the sum of even-indexed and odd-indexed array elements equal.

Problem Constraints

1 <= N <= 105
-105 <= A[i] <= 105
Sum of all elements of A <= 109

Input Format

First argument contains an array A of integers of size N

Output Format

Return the count of array indices such that removing an element from these indices makes the sum of even-indexed and odd-indexed array elements equal.

Example Input

Input 1:
A = [2, 1, 6, 4]
Input 2:

A = [1, 1, 1]

Example Output

Output 1:
1
Output 2:

3

**Example In-place Prefix Sum**
Problem Description

Given an array A of N integers. Construct prefix sum of the array in the given array itself.

Problem Constraints

1 <= N <= 105
1 <= A[i] <= 103

Input Format

Only argument A is an array of integers.

Output Format

Return an array of integers denoting the prefix sum of the given array.

Example Input

Input 1:

A = [1, 2, 3, 4, 5]
Input 2:

A = [4, 3, 2]

Example Output

Output 1:

[1, 3, 6, 10, 15]
Output 2:

[4, 7, 9]

Example Explanation

Explanation 1:

The prefix sum array of [1, 2, 3, 4, 5] is [1, 3, 6, 10, 15].
Explanation 2:

The prefix sum array of [4, 3, 2] is [4, 7, 9].


**Example :  Equilibrium index of an array**

Problem Description
You are given an array A of integers of size N.
Your task is to find the equilibrium index of the given array
The equilibrium index of an array is an index such that the sum of elements at lower indexes is equal to the sum of elements at higher indexes.
If there are no elements that are at lower indexes or at higher indexes, then the corresponding sum of elements is considered as 0.

Note:
- Array indexing starts from 0.
- If there is no equilibrium index then return -1.
- If there are more than one equilibrium indexes then return the minimum index.

Problem Constraints

1 <= N <= 105
-105 <= A[i] <= 105

Input Format

First arugment is an array A .

Output Format

Return the equilibrium index of the given array. If no such index is found then return -1.

Example Input

Input 1:
A = [-7, 1, 5, 2, -4, 3, 0]
Input 2:

A = [1, 2, 3]

Example Output

Output 1:
3
Output 2:

-1

Example Explanation

Explanation 1:
i   Sum of elements at lower indexes    Sum of elements at higher indexes
0                   0                                   7
1                  -7                                   6
2                  -6                                   1
3                  -1                                  -1
4                   1                                   3
5                  -3                                   0
6                   0                                   0

3 is an equilibrium index, because: 
A[0] + A[1] + A[2] = A[4] + A[5] + A[6]
Explanation 1:

i   Sum of elements at lower indexes    Sum of elements at higher indexes
0                   0                                   5
1                   1                                   3
2                   3                                   0
Thus, there is no such index.



Expected Output
Provide sample input and click run to see the correct output for the provided input. Use this to improve your problem understanding and test edge cases