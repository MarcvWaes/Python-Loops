# Python-Loops

# Challenge:
- The provided code stub reads an integer, n, from STDIN. For all non-negative integers i<n, print i^2.
- Example:
- n = 3
- The list of non-negative integers that are less than n=3 is [0,1,2]. Print the square of each number on a separate line.
- Print:
- 0
- 1
- 4

- The first and only line contains the integer, n.

- Constraints: 1 <= n <= 20

# Solution:
- n = int(input())
-     for i in range (n):
-         print(i*i)
