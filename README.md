# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#Write a python Program to find the gcd of a number using function.
#Developed by: Santhosh L
#reg no: 212222100046

def gcd():
    num1,num2=int(input()),int(input())
    if(num1>num2):
        smaller=num2
    else:
        smaller=num1
    for i in range(1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcdvalue=i
    print("GCD of two numbers is:",gcdvalue)
```

## Output:
![GCD](https://github.com/sandy29l/GCD-of-two-numbers/assets/123359969/9fba17d8-fb3a-477e-a770-679f1ef43867)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
