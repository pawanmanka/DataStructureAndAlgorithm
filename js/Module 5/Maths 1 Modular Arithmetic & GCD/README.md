
**Q1. Pair Sum divisible by M**

Problem Description

Given an array of integers A and an integer B, find and return the number of pairs in A whose sum is divisible by B.

Since the answer may be large, return the answer modulo (109 + 7).

Note: Ensure to handle integer overflow when performing the calculations.


Problem Constraints

1 <= length of the array <= 100000
1 <= A[i] <= 109
1 <= B <= 106



Input Format

The first argument given is the integer array A.
The second argument given is the integer B.



Output Format

Return the total number of pairs for which the sum is divisible by B modulo (109 + 7).



Example Input

Input 1:

 A = [1, 2, 3, 4, 5]
 B = 2
Input 2:

 A = [5, 17, 100, 11]
 B = 28


Example Output

Output 1:

 4
Output 2:

 1


Example Explanation

Explanation 1:
 All pairs which are divisible by 2 are (1,3), (1,5), (2,4), (3,5). 
 So total 4 pairs.
Explanation 2:
 There is only one pair which is divisible by 28 is (17, 11)

**Q2. Greatest Common Divisor** 

Problem Description

Given 2 non-negative integers A and B, find gcd(A, B)



GCD of 2 integers A and B is defined as the greatest integer 'g' such that 'g' is a divisor of both A and B. Both A and B fit in a 32 bit signed integer.

Note: DO NOT USE LIBRARY FUNCTIONS.





Problem Constraints

0 <= A, B <= 109



Input Format

First argument is an integer A.
Second argument is an integer B.



Output Format

Return an integer denoting the gcd(A, B).



Example Input

Input 1:

A = 4
B = 6
Input 2:

A = 6
B = 7


Example Output

Output 1:

 2
Output 2:

 1


Example Explanation

Explanation 1:

 2 divides both 4 and 6
Explanation 2:

 1 divides both 6 and 7

**Q3. Delete one**

Problem Description

Given an integer array A of size N. You have to delete one element such that the GCD(Greatest common divisor) of the remaining array is maximum.

Find the maximum value of GCD.



Problem Constraints

2 <= N <= 105
1 <= A[i] <= 109



Input Format

First argument is an integer array A.



Output Format

Return an integer denoting the maximum value of GCD.



Example Input

Input 1:

 A = [12, 15, 18]
Input 2:

 A = [5, 15, 30]




Example Output

Output 1:

 6
Output 2:

 15




Example Explanation

Explanation 1:

 If you delete 12, gcd will be 3.
 If you delete 15, gcd will be 6.
 If you delete 18, gcd will 3.
 Maximum value of gcd is 6.
Explanation 2:

 If you delete 5, gcd will be 15.
 If you delete 15, gcd will be 5.
 If you delete 30, gcd will be 5.
 Maximum value of gcd is 15.

**Q4. Mod Sum**

Problem Description

Given an array of integers A, calculate the sum of A [ i ] % A [ j ] for all possible i, j pairs. Return sum % (109 + 7) as an output.



Problem Constraints

1 <= length of the array A <= 105

1 <= A[i] <= 103



Input Format

The only argument given is the integer array A.



Output Format

Return a single integer denoting sum % (109 + 7).



Example Input

Input 1:

 A = [1, 2, 3]
Input 2:

 A = [17, 100, 11]


Example Output

Output 1:

 5
Output 2:

 61


Example Explanation

Explanation 1:

 (1 % 1) + (1 % 2) + (1 % 3) + (2 % 1) + (2 % 2) + (2 % 3) + (3 % 1) + (3 % 2) + (3 % 3) = 5

**Q1. A, B and Modulo**

Problem Description

Given two integers A and B, find the greatest possible positive integer M, such that A % M = B % M.



Problem Constraints

1 <= A, B <= 109
A != B



Input Format

The first argument is an integer A.
The second argument is an integer B.



Output Format

Return an integer denoting the greatest possible positive M.



Example Input

Input 1:

A = 1
B = 2
Input 2:

A = 5
B = 10


Example Output

Output 1:

1
Output 2:

5


Example Explanation

Explanation 1:

1 is the largest value of M such that A % M == B % M.
Explanation 2:

For M = 5, A % M = 0 and B % M = 0.

No value greater than M = 5, satisfies the condition.

**Q2. Largest Coprime Divisor**

Problem Description

You are given two positive numbers A and B . You need to find the maximum valued integer X such that:

X divides A i.e. A % X = 0
X and B are co-prime i.e. gcd(X, B) = 1


Problem Constraints

1 <= A, B <= 109



Input Format

First argument is an integer A.
Second argument is an integer B.



Output Format

Return an integer maximum value of X as descibed above.



Example Input

Input 1:

 A = 30
 B = 12
Input 2:

 A = 5
 B = 10


Example Output

Output 1:

 5
Output 2:

 1


Example Explanation

Explanation 1:

 All divisors of A are (1, 2, 3, 5, 6, 10, 15, 30). 
 The maximum value is 5 such that A%5 == 0 and gcd(5,12) = 1
Explanation 2:

 1 is the only value such that A%5 == 0 and gcd(1,10) = 1

**Q3. Divisor game**

Problem Description

Scooby has 3 three integers A, B, and C.





Scooby calls a positive integer special if it is divisible by B and it is divisible by C. You need to tell the number of special integers less than or equal to A.








Problem Constraints

1 <= A, B, C <= 109



Input Format

First argument is a positive integer A
Second argument is a positive integer B
Third argument is a positive integer C



Output Format

One integer corresponding to the number of special integers less than or equal to A.



Example Input

Input 1:

 A = 12
 B = 3
 C = 2
Input 2:

 A = 6
 B = 1
 C = 4


Example Output

Output 1:

 2
Output 2:

 1


Example Explanation

Explanation 1:

 The two integers divisible by 2 and 3 and less than or equal to 12 are 6,12.
Explanation 2:

 Only 4 is a positive integer less than equal to 6 which is divisible by 1 and 4.