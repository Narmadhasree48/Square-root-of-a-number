# Find the square root of a number

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

Program to find the square root for the given number(newton's method) using function.
```Python
Developed by:NARMADHA SREE S
RegisterNumber:212223240105
def newton_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))

```
## Output:
![alt text](<Screenshot 2024-03-23 150228-1.png>)
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
