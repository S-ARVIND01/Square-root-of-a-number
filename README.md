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
```python
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: ARVIND S
RegisterNumber:  212222240012
*/
n1 = int(input())
x=1
for i in range(100):
    x = 0.5*(x + n1/x)
print("Square root of the number:",x)
```

## Output:

![Screenshot 2023-10-04 211233](https://github.com/S-ARVIND01/Square-root-of-a-number/assets/118707337/a2fd31d8-8f5b-4834-b31b-144c59df70ed)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
