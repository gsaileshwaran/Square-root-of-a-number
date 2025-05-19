# Find the square root of a number

NAME : Saileshwaran Ganesan

REG NO: 212224230237

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Saileshwaran Ganesan
RegisterNumber:  212224230237
*/
```
```
def newton_method(n,n_iter):
    a=float(n)
    for i in range(n_iter):
        n=0.5*(n+a/n)
    return n
a=int(input())
n_iter=100
n=newton_method(a,n_iter)
print(f"Square root of the number: {n}")
```

## Output:


![image](https://github.com/user-attachments/assets/541703ad-13db-4666-a92c-d00543936321)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
