**Q1. Find All Primes**

Problem Description

Given an integer A. Find the list of all prime numbers in the range [1, A].


Problem Constraints

1 <= A <= 106



Input Format

Only argument A is an integer.



Output Format

Return a sorted array of prime number in the range [1, A].



Example Input

Input 1:
A = 7
Input 2:
A = 12


Example Output

Output 1:
[2, 3, 5, 7]
Output 2:
[2, 3, 5, 7, 11]


Example Explanation

For Input 1:
The prime numbers from 1 to 7 are 2, 3, 5 and 7.
For Input 2:
The prime numbers from 1 to 12 are 2, 3, 5, 7 and 11.

**Q2. Count of divisors**

Problem Description

Given an array of integers A, find and return the count of divisors of each element of the array.







NOTE: The order of the resultant array should be the same as the input array.










Problem Constraints

1 <= length of the array <= 100000
1 <= A[i] <= 106



Input Format

The only argument given is the integer array A.



Output Format

Return the count of divisors of each element of the array in the form of an array.



Example Input

Input 1:

 A = [2, 3, 4, 5]
Input 2:

 A = [8, 9, 10]


Example Output

Output 1:

 [2, 2, 3, 2]
Output 1:

 [4, 3, 4]


Example Explanation

Explanation 1:

 The number of divisors of 2 : [1, 2], 3 : [1, 3], 4 : [1, 2, 4], 5 : [1, 5]
 So the count will be [2, 2, 3, 2].
Explanation 2:

 The number of divisors of 8 : [1, 2, 4, 8], 9 : [1, 3, 9], 10 : [1, 2, 5, 10]
 So the count will be [4, 3, 4].

**Q3. Sorted Permutation Rank**

Problem Description

Given a string A. Find the rank of the string amongst its permutations sorted lexicographically.
Assume that no characters are repeated.

Note: The answer might not fit in an integer, so return your answer % 1000003



Problem Constraints

1 <= |A| <= 1000



Input Format

First argument is a string A.



Output Format

Return an integer denoting the rank of the given string.



Example Input

Input 1:

A = "acb"
Input 2:

A = "a"


Example Output

Output 1:

2
Output 2:

1


Example Explanation

Explanation 1:

Given A = "acb".
The order permutations with letters 'a', 'c', and 'b' : 
abc
acb
bac
bca
cab
cba
So, the rank of A is 2.
Explanation 2:

Given A = "a".
Rank is clearly 1.

**Q4. Prime Sum**

Problem Description

Given an even number A ( greater than 2 ), return two prime numbers whose sum will be equal to the given number.







If there is more than one solution possible, return the lexicographically smaller solution.

If [a, b] is one solution with a <= b, and [c,d] is another solution with c <= d, then 
[a, b] < [c, d], If a < c OR a==c AND b < d. 
NOTE: A solution will always exist. Read Goldbach's conjecture.








Problem Constraints

4 <= A <= 2*107



Input Format

First and only argument of input is an even number A.



Output Format

Return a integer array of size 2 containing primes whose sum will be equal to given number.



Example Input

 4


Example Output

 [2, 2]


Example Explanation

 There is only 1 solution for A = 4.

 **Q1. Lucky Numbers**

Problem Description

A lucky number is a number that has exactly 2 distinct prime divisors.





You are given a number A, and you need to determine the count of lucky numbers between the range 1 to A (both inclusive).







Problem Constraints

1 <= A <= 50000



Input Format

The first and only argument is an integer A.



Output Format

Return an integer i.e the count of lucky numbers between 1 and A, both inclusive.



Example Input

Input 1:

 A = 8
Input 2:

 A = 12


Example Output

Output 1:

 1
Output 2:

 3


Example Explanation

Explanation 1:

 Between [1, 8] there is only 1 lucky number i.e 6.
 6 has 2 distinct prime factors i.e 2 and 3.
Explanation 2:

 Between [1, 12] there are 3 lucky number: 6, 10 and 12.

**Q2. Excel Column Number**

Problem Description

Given a column title as appears in an Excel sheet, return its corresponding column number.



Problem Constraints

1 <= length of the column title <= 5



Input Format

The only argument is a string that represents the column title in the excel sheet.



Output Format

Return a single integer that represents the corresponding column number.



Example Input

Input 1:

 AB
Input 2:

 BB


Example Output

Output 1:

 28
Output 2:

 54


Example Explanation

Explanation 1:

 A -> 1
 B -> 2
 C -> 3
 ...
 Z -> 26
 AA -> 27
 AB -> 28
Explanation 2:

 A -> 1
 B -> 2
 C -> 3
 ...
 Z -> 26
 AA -> 27
 AB -> 28
 ...
 AZ -> 52
 BA -> 53
 BB -> 54

