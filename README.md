# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Mukil kumar v
RegisterNumber:  22008798
*/
def gcd():
    x=int(input())
    y=int(input())
    if x>y:
       smaller = y
    else:
       smaller = x
    for i in range(1,smaller+1):
        if((x%i==0)and(y%i==0)):
            gc=i
    print("GCD of two numbers is:",gc)
```

## Output:
![gcd of two number](./gcd.PNG)
![gcd](./img/Screenshot_20230118_110019.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
