# Exp.No: 2c

## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM

To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.
3. Define a lambda function `relation` that takes two arguments `x` and `y`.
4. The lambda function compares the numbers and prints:

   * If `x > y`, then it prints: "`num2` is smaller than `num1`".
   * If `x < y`, then it prints: "`num1` is smaller than `num2`".
   * If `x == y`, then it prints: "`num1` and `num2` are equal".
5. Call the lambda function by passing `num1` and `num2` as arguments.
6. Terminate the program.

---

### PROGRAM

```python
#Reg.No: 212223060231
#Name: Royce Niran George A

num1 = eval(input("Enter first number: "))
num2 = eval(input("Enter second number: "))

relation = lambda x, y: print(
    f"{y} is smaller than {x}" if x > y else
    f"{x} is smaller than {y}" if x < y else
    f"{x} and {y} are equal"
)

relation(num1, num2)
```

---

### OUTPUT
![image](https://github.com/user-attachments/assets/9a63cba2-ad68-4bfe-a047-28b9fd2b5973)

---

### RESULT

Thus, the Python program to compare two numbers using a lambda function was written and executed successfully.
