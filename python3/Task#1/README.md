## Project Euler #1: Multiples of 3 and 5
> This problem is a programming version of Problem 1 from <a href="projecteuler.net" >projecteuler.net</a>

### Problem
If we list all the natural numbers below `10` that are multiples of `3` or `5`, we get `3`,`5`, `6`, and `9`. The sum of these multiples is `23`.

Find the sum of all the multiples of, `3` or `5` below `N`. 

**Input Format**
First line contains *T*  that denotes the number of test cases. This is followed by *t* lines, each containing an integer,*N* .

**Constraints**
- 1 ≤ T ≤ 10<sup>5</sup>
- 1 ≤ N ≤ 10<sup>9</sup>

**Output Format**
For each test case, print an integer that denotes the sum of all the multiples of `3` or `5` below `N`.

**Sample Input**
```
2
10
100
```
**Sample Output**
```
23
2318
```
**Explanation**

For N = 10 , if we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3,5,6 and 9 . The sum of these multiples is 23.

Similarly for N = 100, we get 2318.

Python3
```
#!/bin/python3

import sys


t = int(input().strip())
for a0 in range(t):
    n = int(input().strip())

```
