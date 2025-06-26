**Q1. Length of longest consecutive ones**

Given a binary string A. It is allowed to do at most one swap between any 0 and 1. Find and return the length of the longest consecutive 1’s that can be achieved.


Input Format

The only argument given is string A.
Output Format

Return the length of the longest consecutive 1’s that can be achieved.
Constraints

1 <= length of string <= 1000000
A contains only characters 0 and 1.
For Example

Input 1:
    A = "111000"
Output 1:
    3

Input 2:
    A = "111011101"
Output 2:
    7

**Q2. Row to Column Zero**

Problem Description

You are given a 2D integer matrix A, make all the elements in a row or column zero if the A[i][j] = 0. Specifically, make entire ith row and jth column zero.



Problem Constraints

1 <= A.size() <= 103

1 <= A[i].size() <= 103

0 <= A[i][j] <= 103



Input Format

First argument is a 2D integer matrix A.



Output Format

Return a 2D matrix after doing required operations.



Example Input

Input 1:

[1,2,3,4]
[5,6,7,0]
[9,2,0,4]


Example Output

Output 1:

[1,2,0,0]
[0,0,0,0]
[0,0,0,0]


Example Explanation

Explanation 1:

A[2][4] = A[3][3] = 0, so make 2nd row, 3rd row, 3rd column and 4th column zero.

**Q3. Majority Element**

Problem Description

Given an array of size N, find the majority element. The majority element is the element that appears more than floor(n/2) times.
You may assume that the array is non-empty and the majority element always exists in the array.



Problem Constraints

1 <= N <= 5*105
1 <= num[i] <= 109


Input Format

Only argument is an integer array.


Output Format

Return an integer.


Example Input

Input 1:
[2, 1, 2]
Input 2:
[1, 1, 1]


Example Output

Input 1:
2
Input 2:
1


Example Explanation

For Input 1:
2 occurs 2 times which is greater than 3/2.
For Input 2:
 1 is the only element in the array, so it is majority

**Q1. N/3 Repeat Number**

Problem Description

You're given a read-only array of N integers. Find out if any integer occurs more than N/3 times in the array in linear time and constant additional space.
If so, return the integer. If not, return -1.

If there are multiple solutions, return any one.

Note: Read-only array means that the input array should not be modified in the process of solving the problem



Problem Constraints

1 <= N <= 7*105
1 <= A[i] <= 109


Input Format

The only argument is an integer array A.


Output Format

Return an integer.


Example Input

Input 1:
[1 2 3 1 1]
Input 2:
[1 2 3]


Example Output

Output 1:
1
Output 2:
-1
**Q2. Check anagrams**
Problem Description

You are given two lowercase strings A and B each of length N. Return 1 if they are anagrams to each other and 0 if not.

Note : Two strings A and B are called anagrams to each other if A can be formed after rearranging the letters of B.


Problem Constraints

1 <= N <= 105
A and B are lowercase strings


Input Format

Both arguments A and B are a string.


Output Format

Return 1 if they are anagrams and 0 if not


Example Input

Input 1:
A = "cat"
B = "bat"
Input 2:
A = "secure"
B = "rescue"


Example Output

Output 1:
0
Output 2:
1

**Q3. Colorful Number**
Problem Description

Given a number A, find if it is COLORFUL number or not.

If number A is a COLORFUL number return 1 else, return 0.

What is a COLORFUL Number:

A number can be broken into different consecutive sequence of digits. 
The number 3245 can be broken into sequences like 3, 2, 4, 5, 32, 24, 45, 324, 245 and 3245. 
This number is a COLORFUL number, since the product of every consecutive sequence of digits is different



Problem Constraints

1 <= A <= 2 * 109



Input Format

The first and only argument is an integer A.



Output Format

Return 1 if integer A is COLORFUL else return 0.



Example Input

Input 1:

 A = 23
Input 2:

 A = 236


Example Output

Output 1:

 1
Output 2:

 0


Example Explanation

Explanation 1:

 Possible Sub-sequences: [2, 3, 23] where
 2 -> 2 
 3 -> 3
 23 -> 6  (product of digits)
 This number is a COLORFUL number since product of every digit of a sub-sequence are different. 
Explanation 2:

 Possible Sub-sequences: [2, 3, 6, 23, 36, 236] where
 2 -> 2 
 3 -> 3
 6 -> 6
 23 -> 6  (product of digits)
 36 -> 18  (product of digits)
 236 -> 36  (product of digits)
 This number is not a COLORFUL number since the product sequence 23  and sequence 6 is same. 

