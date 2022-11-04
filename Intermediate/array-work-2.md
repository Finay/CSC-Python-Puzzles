### Given an array of numbers, print a new array where each nth value is the nth + n+1th + n value of the original array
```
Eg input:
1 5 2 8
Eg output:
6 8 12 11
Explanation:
6 = 1(nth) + 5(n+1th or next number) + 0(index)
8 = 5(nth) + 2(n+1th or next number) + 1(index)
12 = 2(nth) + 8(n+1th or next number) + 2(index)
11 = 8(nth) + none(n+1th or next number) + 3(index)
```