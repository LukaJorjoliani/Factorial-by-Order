# Factorial-by-Order
User choices of which number they would like to see factorial of

n= int(raw_input("Let me return factorial of: "))
def factorial(n):
    if n==0:
        return 1
    return n * factorial(n-1)

print factorial(n)

