# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# step1:
 Define a function.
# step2:
 Get the two numbers from the user.
# step3:
 Compare the two values, to find the smaller number.
# step4:
 Use for() and if() loop to find the GCD of the two numbers.
 # step 5:
 print gcd

## Program:
```````
# Program to find the gcd of two number using function.
# Developed by: R ABDULLAH
# RegisterNumber: 23013613 
def gcd():
    num1=int(input())
    num2=int(input())
    if num1>num2:
        min=num2
    else:
        min=num1
    for i in range(1,min+1):
        if(num1%i==0 and num2%i==0):
            gcd=i
    print("GCD of two numbers is:",gcd)
```````

## Output:
![Alt text](<Screenshot 2023-11-26 142628.png>)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
