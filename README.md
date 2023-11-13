# Find the square root of a number
## DATE:29.08.2023
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
##Program to find the square root for the given number(newton's method) using function.
##Developed by: PAVANA G
##RegisterNumber:  212222230105

def sroot(n):
    a=float(n)
    for i in range(100):
        n=0.5 *(n + a / n)
    return n
a=int(input())
print("Square root of the number:",sroot(a))
```
## Output:
![image](https://github.com/gpavana/Square-root-of-a-number/assets/118787343/6c54a542-b513-4be5-84d8-0c23ad1adbad)
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
