# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
# Reg.No:212223060057
# Name:DINESH KUMAR A
# Add your Code Here

def perfectNumber(n):
    factor_sum = 0
    for i in range(1, n // 2 + 1):
        if n % i == 0:
            factor_sum += i

    if factor_sum == n:
        print(f"{n} is a Perfect Number")
    else:
        print(f"{n} is NOT a Perfect Number")

# Taking input from user
num = int(input("Enter a number: "))
perfectNumber(num)


```
### OUTPUT
```
Enter a number: 28
28 is a Perfect Number

```
or
```
Enter a number: 10
10 is NOT a Perfect Number

```

### RESULT
Thus, the Python program to check whether a given number is a Perfect Number using functions was successfully implemented and executed.
