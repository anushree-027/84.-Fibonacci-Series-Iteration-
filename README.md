# 84.-Fibonacci-Series-Iteration-
a, b = 0, 1
n = int(input("Enter the number of terms in the sequence: "))

print(a, b, end=" ")
for _ in range(n-2):
    c = a + b
    print(c, end=" ")
    a, b = b, c
