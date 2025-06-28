**Q1. Rotated Sorted Array Search**

Problem Description

Given a sorted array of integers A of size N and an integer B, 
where array A is rotated at some pivot unknown beforehand.

For example, the array [0, 1, 2, 4, 5, 6, 7] might become [4, 5, 6, 7, 0, 1, 2].

Your task is to search for the target value B in the array. If found, return its index; otherwise, return -1.

You can assume that no duplicates exist in the array.

NOTE: You are expected to solve this problem with a time complexity of O(log(N)).


Problem Constraints

1 <= N <= 1000000
1 <= A[i] <= 109
All elements in A are Distinct.


Input Format

The First argument given is the integer array A.
The Second argument given is the integer B.


Output Format

Return index of B in array A, otherwise return -1


Example Input

Input 1:

A = [4, 5, 6, 7, 0, 1, 2, 3]
B = 4 
Input 2:

A : [ 9, 10, 3, 5, 6, 8 ]
B : 5


Example Output

Output 1:

 0 
Output 2:

 3


Example Explanation

Explanation 1:

Target 4 is found at index 0 in A. 
Explanation 2:

Target 5 is found at index 3 in A.


**Q2. Median of Array**

Problem Description

There are two sorted arrays A and B of sizes N and M respectively.

Find the median of the two sorted arrays ( The median of the array formed by merging both the arrays ).

NOTE:

The overall run time complexity should be O(log(m+n)).
IF the number of elements in the merged array is even, then the median is the average of (n/2)th and (n/2+1)th element. For example, if the array is [1 2 3 4], the median is (2 + 3) / 2.0 = 2.5.


Problem Constraints

1 <= N + M <= 2*106



Input Format

The first argument is an integer array A of size N.
The second argument is an integer array B of size M.



Output Format

Return a decimal value denoting the median of two sorted arrays.



Example Input

Input 1:

 A = [1, 4, 5]
 B = [2, 3]
Input 2:

 A = [1, 2, 3]
 B = [4]


Example Output

Output 1:

 3.0
Output 2:

 2.5


Example Explanation

Explanation 1:

 The median of both the sorted arrays will be 3.0.
Explanation 2:

 The median of both the sorted arrays will be (2+3)/2 = 2.5.

**Q3. Ath Magical Number**

Problem Description

You are given three positive integers, A, B, and C.

Any positive integer is magical if divisible by either B or C.

Return the Ath smallest magical number. Since the answer may be very large, return modulo 109 + 7.

Note: Ensure to prevent integer overflow while calculating.



Problem Constraints

1 <= A <= 109

2 <= B, C <= 40000



Input Format

The first argument given is an integer A.

The second argument given is an integer B.

The third argument given is an integer C.



Output Format

Return the Ath smallest magical number. Since the answer may be very large, return modulo 109 + 7.



Example Input

Input 1:

 A = 1
 B = 2
 C = 3
Input 2:

 A = 4
 B = 2
 C = 3


Example Output

Output 1:

 2
Output 2:

 6


Example Explanation

Explanation 1:

 1st magical number is 2.
Explanation 2:

 First four magical numbers are 2, 3, 4, 6 so the 4th magical number is 6.

**Q4. Square Root of Integer**

Problem Description

Given an integer A. Compute and return the square root of A.
If A is not a perfect square, return floor(sqrt(A)).

NOTE: 
   The value of A*A can cross the range of Integer.
   Do not use the sqrt function from the standard library. 
   Users are expected to solve this in O(log(A)) time.


Problem Constraints

0 <= A <= 109


Input Format

The first and only argument given is the integer A.


Output Format

Return floor(sqrt(A))


Example Input

Input 1:

 11
Input 2:

 9


Example Output

Output 1:

 3
Output 2:

 3


Example Explanation

Explanation 1:
When A = 11 , square root of A = 3.316. It is not a perfect square so we return the floor which is 3.
Explanatino 2:
When A = 9 which is a perfect square of 3, so we return 3.


**Q1. ADD OR NOT**

Problem Description

Given an array of integers A of size N and an integer B.

In a single operation, any one element of the array can be increased by 1. You are allowed to do at most B such operations.

Find the number with the maximum number of occurrences and return an array C of size 2, where C[0] is the number of occurrences, and C[1] is the number with maximum occurrence.
If there are several such numbers, your task is to find the minimum one.



Problem Constraints

1 <= N <= 105

-109 <= A[i] <= 109

0 <= B <= 109



Input Format

The first argument given is the integer array A.
The second argument given is the integer B.



Output Format

Return an array C of size 2, where C[0] is number of occurence and C[1] is the number with maximum occurence.



Example Input

Input 1:

 A = [3, 1, 2, 2, 1]
 B = 3
Input 2:

 A = [5, 5, 5]
 B = 3


Example Output

Output 1:

 [4, 2]
Output 2:

 [3, 5]


Example Explanation

Explanation 1:

 Apply operations on A[2] and A[4]
 A = [3, 2, 2, 2, 2]
 Maximum occurence =  4
 Minimum value of element with maximum occurence = 2
Explanation 2:

 A = [5, 5, 5]
 Maximum occurence =  3
 Minimum value of element with maximum occurence = 5

**Q2. Find Smallest Again**
Problem Description

Given an integer array A of size N.

If we store the sum of each triplet of the array A in a new list, then find the Bth smallest element among the list.

NOTE: A triplet consists of three elements from the array. Let's say if A[i], A[j], A[k] are the elements of the triplet then i < j < k.



Problem Constraints

3 <= N <= 500
1 <= A[i] <= 108
1 <= B <= (N*(N-1)*(N-2))/6



Input Format

The first argument is an integer array A.
The second argument is an integer B.



Output Format

Return an integer denoting the Bth element of the list.



Example Input

Input 1:

 A = [2, 4, 3, 2]
 B = 3
Input 2:

 A = [1, 5, 7, 3, 2]
 B = 9


Example Output

Output 1:

 9 
Output 2:

 14


Example Explanation

Explanation 1:

 All the triplets of the array A are:

 (2, 4, 3) = 9
 (2, 4, 2) = 8
 (2, 3, 2) = 7
 (4, 3, 2) = 9

 So the 3rd smallest element is 9.


**Q3. Matrix Median**

Problem Description

Given a matrix of integers A of size N x M in which each row is sorted.


Find and return the overall median of matrix A.

NOTE: No extra memory is allowed.

NOTE: Rows are numbered from top to bottom and columns are numbered from left to right.



Problem Constraints

1 <= N, M <= 10^5

1 <= N*M <= 10^6

1 <= A[i] <= 10^9

N*M is odd



Input Format

The first and only argument given is the integer matrix A.



Output Format

Return the overall median of matrix A.



Example Input

Input 1:

A = [   [1, 3, 5],
        [2, 6, 9],
        [3, 6, 9]   ] 
Input 2:

A = [   [5, 17, 100]    ]


Example Output

Output 1:

 5 
Output 2:

 17


Example Explanation

Explanation 1:

A = [1, 2, 3, 3, 5, 6, 6, 9, 9]
Median is 5. So, we return 5. 
Explanation 2:

Median is 17.
