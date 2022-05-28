# Factorial of number using loops
#Using For loops

n = int(input("Enter any number: "))

f = 1

for i in range(1, n+1):
    f = f * i

print(f"Factorial of number: {f}")

#Using While loops

n = int(input("#find the factorial of numberEnter the number: "))

f = 1

i = 1

while i <= n:
    f = f * i
    i = i + 1

print(f'Factorial of n: {f}')
