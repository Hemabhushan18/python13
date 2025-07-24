# python13
Fibonacci series uing recursions

def fib(n):
    if n<=1:
        return n
    return fib(n-1)+(n-2)
terms= int(input("Enter number of terms to print:"))
print("fibonacci series...")
for i in range(terms):
    print(fib(i), end= ' ')
