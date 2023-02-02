# CSA0861-PYTHON
def fib(n):
    if n <= 1:
        return n
    return fib(n-1) + fib(n-2)
def distinctways(s):
    return fib(s+1)
s=2
print("number of distinct ways= "),
print (distinctways(s))

