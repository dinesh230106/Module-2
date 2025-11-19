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

n=int(input())
sum1=0
for i in range(1, n):
    if(n % i == 0):
        sum1 = sum1 + i
if(sum1 == n):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")


```
### OUTPUT
<img width="1149" height="277" alt="image" src="https://github.com/user-attachments/assets/9f204517-0af4-4219-82a1-24cd7005c85d" />


### RESULT
Thus, the Python program to check whether a given number is a Perfect Number using functions was successfully implemented and executed.
