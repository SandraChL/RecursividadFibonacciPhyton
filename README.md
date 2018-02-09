# RecursividadFibonacciPhyton
se mostrara el codigo en phyton de la recursividad

Recursividad 1

def fib(n):
    a, b = 0,1
    while a < n:
        print(a, end=' ')
        a, b = b, a+b
    print()
fib(1000)


Recursividad 2

def fib(n):
    a, b = 0,1
    while a < n:
        print(a, end=' ')
        a, b = b, a + b
m = int(input("Ingresa límite máximo de la sucesión: "))     
fib(m)




