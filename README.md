# DATE:
# EXP.NO: 5
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
```
/*
# Program to find the square root for the given number(newton's method) using function.
# Developed by: RUDESH KANNA R
# RegisterNumber:  24900303
def newton_sqrt(number, tolerance=1e-10):
  
    guess = number / 2.0
    
    while True:
        
        better_guess = 0.5 * (guess + number / guess)
        
        if abs(better_guess - guess) < tolerance:
            return better_guess
        
        guess = better_guess

number = float(input(""))
sqrt = newton_sqrt(number)
print(f"Square root of the number: {sqrt}")  
*/
```

## Output:
![image](https://github.com/user-attachments/assets/8a4281a7-aa59-4849-8b84-c72918b582cc)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
