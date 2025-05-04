# Exp.No: 2b

## FUNCTIONS - PERFECT NUMBER

### AIM

To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.
2. Read the number `n` from the user using `input()`.
3. Convert the input to an integer.
4. Define the function `perfectNumber(n)` with the following steps:

   * Initialize a variable `factor_sum` to 0.
   * Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).
   * If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.
   * If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.
5. Terminate the program.

---

### PROGRAM

```python
#Reg.No: 12345678
#Name: Royce Niran George

def perfectNumber(n):
    factor_sum = 0
    for i in range(1, n // 2 + 1):
        if n % i == 0:
            factor_sum += i
    if factor_sum == n:
        print(n, "is a Perfect Number.")
    else:
        print(n, "is NOT a Perfect Number.")

# Main Program
num = int(input("Enter a number: "))
perfectNumber(num)
```

---

### OUTPUT


![image](https://github.com/user-attachments/assets/50f41858-db58-4d00-9da7-6b3282080743)

### RESULT

Thus, the Python program to check whether a number is a perfect number using functions was written and executed successfully.

