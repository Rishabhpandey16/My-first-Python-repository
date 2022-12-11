# My-first-Python-repository
Checking the sequence of numbers as a fabonacci series using python.


import math
def isperfect(x):
    s = int(math.sqrt(x))
    return s*s == x
def isfibonacci(n):
    return ispercet(5*n*n+4) or isperfect(5*n*n-4)
for i in range(1,11):
    if (isfibonacci(i)==True):
        print(i, "is a perfect number")
    else:
        print(i, "is not a fibonacci number")
