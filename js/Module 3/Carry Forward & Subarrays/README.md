**Carry Forward & Subarrays**
#
**Find all the subarrays**

Given A = [1, -2, 5, 2, -1, 6]. Choose all the valid subarrays of the array

**Closest MinMax**

Problem Description

Given an array A, find the size of the smallest subarray such that it contains at least one occurrence of the maximum value of the array

and at least one occurrence of the minimum value of the array.

Problem Constraints

1 <= |A| <= 2000

Input Format

First and only argument is vector A


Output Format

Return the length of the smallest subarray which has at least one occurrence of minimum and maximum element of the array



Example Input

Input 1:

A = [1, 3, 2]
Input 2:

A = [2, 6, 1, 6, 9]


Example Output

Output 1:

 2
Output 2:

 3
 
Example Explanation

Explanation 1:

 Take the 1st and 2nd elements as they are the minimum and maximum elements respectievly.
Explanation 2:

 Take the last 3 elements of the array.


**Example : Special Subsequences "AG"**

Problem Description

You have given a string A having Uppercase English letters.

You have to find how many times subsequence "AG" is there in the given string.

NOTE: Return the answer modulo 109 + 7 as the answer can be very large.

Problem Constraints

1 <= length(A) <= 105

Input Format

First and only argument is a string A.

Output Format

Return an integer denoting the answer.



Example Input

Input 1:

 A = "ABCGAG"
Input 2:

 A = "GAB"


Example Output

Output 1:

 3
Output 2:

 0


Example Explanation

Explanation 1:

 Subsequence "AG" is 3 times in given string 
Explanation 2:

 There is no subsequence "AG" in the given string.


**subarrays  Formula :**

**N*(N + 1)/2**

**Example : Q5. Subarray in given range**

Problem Description

Given an array A of length N, return the subarray from B to C.


Problem Constraints

1 <= N <= 105

1 <= A[i] <= 109

0 <= B <= C < N



Input Format

The first argument A is an array of integers

The remaining argument B and C are integers.



Output Format

Return a subarray


Example Input

Input 1:
A = [4, 3, 2, 6]
B = 1
C = 3
Input 2:

A = [4, 2, 2]
B = 0
C = 1


Example Output

Output 1:
[3, 2, 6]
Output 2:

[4, 2]


Example Explanation

Explanation 1:
The subarray of A from 1 to 3 is [3, 2, 6].
Explanation 2:
The subarray of A from 0 to 1 is [4, 2].

**Q6. Generate all subarrays**
Problem Description

You are given an array A of N integers.
Return a 2D array consisting of all the subarrays of the array

Note : The order of the subarrays in the resulting 2D array does not matter.


Problem Constraints

1 <= N <= 100
1 <= A[i] <= 105


Input Format

First argument A is an array of integers.


Output Format

Return a 2D array of integers in any order.


Example Input

Input 1:
A = [1, 2, 3]
Input 2:
A = [5, 2, 1, 4]


Example Output

Output 1:
[[1], [1, 2], [1, 2, 3], [2], [2, 3], [3]]
Output 2:
[[1 ], [1 4 ], [2 ], [2 1 ], [2 1 4 ], [4 ], [5 ], [5 2 ], [5 2 1 ], [5 2 1 4 ] ]


Example Explanation

For Input 1:
All the subarrays of the array are returned. There are a total of 6 subarrays.
For Input 2:
All the subarrays of the array are returned. There are a total of 10 subarrays.

**Imp Example Q7. Best Time to Buy and Sell Stocks I**

Problem Description

Say you have an array, A, for which the ith element is the price of a given stock on day i.
If you were only permitted to complete at most one transaction (ie, buy one and sell one share of the stock), design an algorithm to find the maximum profit.

Return the maximum possible profit.



Problem Constraints

0 <= A.size() <= 700000



1 <= A[i] <= 107





Input Format

The first and the only argument is an array of integers, A.


Output Format

Return an integer, representing the maximum possible profit.


Example Input

Input 1:
A = [1, 2]
Input 2:

A = [1, 4, 5, 2, 4]


Example Output

Output 1:
1
Output 2:

4


Example Explanation

Explanation 1:
Buy the stock on day 0, and sell it on day 1.
Explanation 2:

Buy the stock on day 0, and sell it on day 2.

**Q1. Count Subarrays starting with 'a'**

Given a string A = "amazon", find the number of subarrays starting with the character 'a'.

**Q2. Pick from both sides!**

Problem Description

You are given an integer array A of size N.

You have to perform B operations. In one operation, you can remove either the leftmost or the rightmost element of the array A.

Find and return the maximum possible sum of the B elements that were removed after the B operations.

NOTE: Suppose B = 3, and array A contains 10 elements, then you can:

Remove 3 elements from front and 0 elements from the back, OR
Remove 2 elements from front and 1 element from the back, OR
Remove 1 element from front and 2 elements from the back, OR
Remove 0 elements from front and 3 elements from the back.


Problem Constraints

1 <= N <= 105

1 <= B <= N

-103 <= A[i] <= 103








Input Format

First argument is an integer array A.

Second argument is an integer B.








Output Format

Return an integer denoting the maximum possible sum of elements you removed.



Example Input

Input 1:






 A = [5, -2, 3 , 1, 2]
 B = 3
Input 2:

 A = [ 2, 3, -1, 4, 2, 1 ]
 B = 4







Example Output

Output 1:






 8
Output 2:

 9







Example Explanation

Explanation 1:






 Remove element 5 from front and element (1, 2) from back so we get 5 + 1 + 2 = 8
Explanation 2:

 Remove the first element and the last 3 elements. So we get 2 + 4 + 2 + 1 = 9


**Q3. Leaders in an array**
Problem Description

Given an integer array A containing N distinct integers, you have to find all the leaders in array A. An element is a leader if it is strictly greater than all the elements to its right side.

NOTE: The rightmost element is always a leader.


Problem Constraints

1 <= N <= 105
1 <= A[i] <= 108


Input Format

There is a single input argument which a integer array A


Output Format

Return an integer array denoting all the leader elements of the array.


Example Input

Input 1:
 A = [16, 17, 4, 3, 5, 2]
Input 2:
 A = [5, 4]


Example Output

Output 1:
[17, 2, 5]
Output 2:
[5, 4]


Example Explanation

Explanation 1:
 Element 17 is strictly greater than all the elements on the right side to it.
 Element 2 is strictly greater than all the elements on the right side to it.
 Element 5 is strictly greater than all the elements on the right side to it.
 So we will return these three elements i.e [17, 2, 5], we can also return [2, 5, 17] or [5, 2, 17] or any other ordering.
Explanation 2:
 Element 5 is strictly greater than all the elements on the right side to it.
 Element 4 is strictly greater than all the elements on the right side to it.
 So we will return these two elements i.e [5, 4], we can also any other ordering.




