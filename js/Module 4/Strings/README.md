**Q1. Toggle Case**

Problem Description

You are given a character string A having length N, consisting of only lowercase and uppercase latin letters.

You have to toggle case of each character of string A. For e.g 'A' is changed to 'a', 'e' is changed to 'E', etc.



Problem Constraints

1 <= N <= 105

A[i] ∈ ['a'-'z', 'A'-'Z']



Input Format

First and only argument is a character string A.



Output Format

Return a character string.



Example Input

Input 1:

 A = "Hello" 
Input 2:

 A = "tHiSiSaStRiNg" 


Example Output

Output 1:

 hELLO 
Output 2:

 ThIsIsAsTrInG 

**Q2. Simple Reverse**

Problem Description

Given a string A, you are asked to reverse the string and return the reversed string.



Problem Constraints

1 <= |A| <= 105

String A consist only of lowercase characters.



Input Format

First and only argument is a string A.



Output Format

Return a string denoting the reversed string.



Example Input

Input 1:

 A = "scaler"
Input 2:

 A = "academy"


Example Output

Output 1:

 "relacs"
Output 2:

 "ymedaca"


Example Explanation

Explanation 1:

 Reverse the given string.

**Q3. Reverse the String**

Problem Description

You are given a string A of size N.


Return the string A after reversing the string word by word.

NOTE:

A sequence of non-space characters constitutes a word.
Your reversed string should not contain leading or trailing spaces, even if it is present in the input string.
If there are multiple spaces between words, reduce them to a single space in the reversed string.



Problem Constraints

1 <= N <= 3 * 105



Input Format

The only argument given is string A.



Output Format

Return the string A after reversing the string word by word.



Example Input

Input 1:
A = "the sky is blue"
Input 2:
A = "this is ib"


Example Output

Output 1:
"blue is sky the"
Output 2:
"ib is this"    


Example Explanation

Explanation 1:
We reverse the string word by word so the string becomes "blue is sky the".
Explanation 2:
We reverse the string word by word so the string becomes "ib is this".

**Q4. Longest Palindromic Substring**

Problem Description

Given a string A of size N, find and return the longest palindromic substring in A.

Substring of string A is A[i...j] where 0 <= i <= j < len(A)

Palindrome string:
A string which reads the same backwards. More formally, A is palindrome if reverse(A) = A.

Incase of conflict, return the substring which occurs first ( with the least starting index).



Problem Constraints

1 <= N <= 6000



Input Format

First and only argument is a string A.



Output Format

Return a string denoting the longest palindromic substring of string A.



Example Input

Input 1:
A = "aaaabaaa"
Input 2:
A = "abba


Example Output

Output 1:
"aaabaaa"
Output 2:
"abba"


Example Explanation

Explanation 1:
We can see that longest palindromic substring is of length 7 and the string is "aaabaaa".
Explanation 2:
We can see that longest palindromic substring is of length 4 and the string is "abba".

**Q5. String operations**
Problem Description

Akash likes playing with strings. One day he thought of applying following operations on the string in the given order:

Concatenate the string with itself.
Delete all the uppercase letters.
Replace each vowel with '#'.
You are given a string A of size N consisting of lowercase and uppercase alphabets. Return the resultant string after applying the above operations.

NOTE: 'a' , 'e' , 'i' , 'o' , 'u' are defined as vowels.



Problem Constraints

1<=N<=100000


Input Format

First argument is a string A of size N.



Output Format

Return the resultant string.



Example Input

Input 1:
A="aeiOUz"
Input 2:
A="AbcaZeoB"


Example Output

Output 1:
"###z###z"
Output 2:
"bc###bc###"


Example Explanation

Explanatino 1:
First concatenate the string with itself so string A becomes "aeiOUzaeiOUz".
Delete all the uppercase letters so string A becomes "aeizaeiz".
Now replace vowel with '#', A becomes "###z###z".
Explanatino 2:
First concatenate the string with itself so string A becomes "AbcaZeoBAbcaZeoB".
Delete all the uppercase letters so string A becomes "bcaeobcaeo".
Now replace vowel with '#', A becomes "bc###bc###".

**Q6. Isalnum()**


Problem Description

You are given a function isalpha() consisting of a character array A.





Return 1 if all the characters of a character array are alphanumeric (a-z, A-Z, and 0-9) else, return 0.





Problem Constraints

1 <= |A| <= 105



Input Format

Only argument is a character array A.



Output Format

Return 1 if all the characters of the character array are alphanumeric (a-z, A-Z and 0-9), else return 0.



Example Input

Input 1:

 A = ['S', 'c', 'a', 'l', 'e', 'r', 'A', 'c', 'a', 'd', 'e', 'm', 'y', '2', '0', '2', '0']
Input 2:

 A = ['S', 'c', 'a', 'l', 'e', 'r', '#', '2', '0', '2', '0']


Example Output

Output 1:

 1
Output 2:

 0


Example Explanation

Explanation 1:

 All the characters are alphanumeric.
Explanation 2:

 All the characters are NOT alphabets i.e ('#').


**Q1. Longest Common Prefix**

Problem Description

Given the array of strings A, you need to find the longest string S, which is the prefix of ALL the strings in the array.


The longest common prefix for a pair of strings S1 and S2 is the longest string S which is the prefix of both S1 and S2.

Example: the longest common prefix of "abcdefgh" and "abcefgh" is "abc".




Problem Constraints

0 <= sum of length of all strings <= 1000000



Input Format

The only argument given is an array of strings A.



Output Format

Return the longest common prefix of all strings in A.



Example Input

Input 1:


A = ["abcdefgh", "aefghijk", "abcefgh"]
Input 2:

A = ["abab", "ab", "abcd"];






Example Output

Output 1:

"a"
Output 2:

"ab"


Example Explanation

Explanation 1:

Longest common prefix of all the strings is "a".
Explanation 2:

Longest common prefix of all the strings is "ab".

**Q2. Count Occurrences**

Problem Description

Find the number of occurrences of bob in string A consisting of lowercase English alphabets.



Problem Constraints

1 <= |A| <= 1000


Input Format

The first and only argument contains the string A, consisting of lowercase English alphabets.


Output Format

Return an integer containing the answer.


Example Input

Input 1:

  "abobc"
Input 2:

  "bobob"


Example Output

Output 1:

  1
Output 2:

  2


Example Explanation

Explanation 1:

  The only occurrence is at second position.
Explanation 2:

  Bob occures at first and third position.

**Q3. Amazing Subarrays**

You are given a string S, and you have to find all the amazing substrings of S.

An amazing Substring is one that starts with a vowel (a, e, i, o, u, A, E, I, O, U).

Input

Only argument given is string S.
Output

Return a single integer X mod 10003, here X is the number of Amazing Substrings in given the string.
Constraints

1 <= length(S) <= 1e6
S can have special characters
Example

Input
    ABEC

Output
    6

Explanation
    Amazing substrings of given string are :
    1. A
    2. AB
    3. ABE
    4. ABEC
    5. E
    6. EC
    here number of substrings are 6 and 6 % 10003 = 6.