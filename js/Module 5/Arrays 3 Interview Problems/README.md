**Q1. Merge Overlapping Intervals**

Problem Description

Given a collection of intervals, merge all overlapping intervals.



Problem Constraints

1 <= Total number of intervals <= 100000.



Input Format

First argument is a list of intervals.



Output Format

Return the sorted list of intervals after merging all the overlapping intervals.



Example Input

Input 1:

[1,3],[2,6],[8,10],[15,18]


Example Output

Output 1:

[1,6],[8,10],[15,18]


Example Explanation

Explanation 1:

Merge intervals [1,3] and [2,6] -> [1,6].
so, the required answer after merging is [1,6],[8,10],[15,18].
No more overlapping intervals present.


**Q2. Merge Intervals**

Problem Description

You have a set of non-overlapping intervals. You are given a new interval [start, end], insert this new interval into the set of intervals (merge if necessary).

You may assume that the intervals were initially sorted according to their start times.



Problem Constraints

0 <= |intervals| <= 105



Input Format

First argument is the vector of intervals

second argument is the new interval to be merged



Output Format

Return the vector of intervals after merging



Example Input

Input 1:

Given intervals [1, 3], [6, 9] insert and merge [2, 5] .
Input 2:

Given intervals [1, 3], [6, 9] insert and merge [2, 6] .


Example Output

Output 1:

 [ [1, 5], [6, 9] ]
Output 2:

 [ [1, 9] ]


Example Explanation

Explanation 1:

(2,5) does not completely merge the given intervals
Explanation 2:

(2,6) completely merges the given intervals



Expected Output
Enter your input as per the following guideline:
There are 3 lines in the input

Line 1 ( Corresponds to arg 1 ) : An array of intervals. First number represents the number of intervals to follow. Then for every interval we get a pair of integers. 
	For example, Intervals: [(1, 3), (6, 9)] will be written as "2 1 3 6 9"(without quotes).

Line 2 & Line 3 ( Corresponds to arg 2 ) : New Interval represented by a pair of integers. 
	For example, Interval: (2, 5) will be written as "2 5"(without quotes)

**Q3. First Missing Integer**

Problem Description

Given an unsorted integer array, A of size N. Find the first missing positive integer.





Note: Your algorithm should run in O(n) time and use constant space.







Problem Constraints

1 <= N <= 1000000

-109 <= A[i] <= 109



Input Format

First argument is an integer array A.



Output Format

Return an integer denoting the first missing positive integer.



Example Input

Input 1:

[1, 2, 0]
Input 2:

[3, 4, -1, 1]
Input 3:

[-8, -7, -6]






Example Output

Output 1:

3
Output 2:

2
Output 3:

1






Example Explanation

Explanation 1:

A = [1, 2, 0]
First positive integer missing from the array is 3.
Explanation 2:

A = [3, 4, -1, 1]
First positive integer missing from the array is 2.
Explanation 3:

A = [-8, -7, -6]
First positive integer missing from the array is 1.

**Q1. Next Permutation**

Problem Description

Implement the next permutation, which rearranges numbers into the numerically next greater permutation of numbers for a given array A of size N.



If such arrangement is not possible, it must be rearranged as the lowest possible order, i.e., sorted in ascending order.

NOTE:



The replacement must be in-place, do not allocate extra memory.
DO NOT USE LIBRARY FUNCTION FOR NEXT PERMUTATION. Use of Library functions will disqualify your submission retroactively and will give you penalty points.


Problem Constraints

1 <= N <= 5 * 105

1 <= A[i] <= 109



Input Format

The first and the only argument of input has an array of integers, A.



Output Format

Return an array of integers, representing the next permutation of the given array.



Example Input

Input 1:

 A = [1, 2, 3]
Input 2:

 A = [3, 2, 1]


Example Output

Output 1:

 [1, 3, 2]
Output 2:

 [1, 2, 3]


Example Explanation

Explanation 1:

 Next permutaion of [1, 2, 3] will be [1, 3, 2].
Explanation 2:

 No arrangement is possible such that the number are arranged into the numerically next greater permutation of numbers.
 So will rearranges it in the lowest possible order.

**Q2. Number of Digit One**

Problem Description

Given an integer A, find and return the total number of digit 1 appearing in all non-negative integers less than or equal to A.



Problem Constraints

0 <= A <= 109



Input Format

The only argument given is the integer A.



Output Format

Return the total number of digit 1 appearing in all non-negative integers less than or equal to A.



Example Input

Input 1:

 A = 10
Input 2:

 A = 11


Example Output

Output 1:

 2
Output 2:

 4


Example Explanation

Explanation 1:

Digit 1 appears in 1 and 10 only and appears one time in each. So the answer is 2.
Explanation 2:

Digit 1 appears in 1(1 time) , 10(1 time) and 11(2 times) only. So the answer is 4.