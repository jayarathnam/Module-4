# Exp.No:4e

## SEB - EXCEPTION HANDLING

### AIM  
Write a python program to Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.

---

### ALGORITHM
1.Input: Accept two numbers from the user — numerator and denominator.

 -Try Block:

-Attempt to divide the numerator by the denominator.

-If successful, store the result.

2.Except Block (ZeroDivisionError):

 -If the denominator is 0, catch the ZeroDivisionError.

 -Set result = "You can't divide with 0".

3.Output:

 -Print the result (either the division result or the error message).


---


---

### PROGRAM

```
a=int(input())
b=int(input())
try:
    print(a/b)
except ZeroDivisionError:
    print("You can't divide with 0")



```

### OUTPUT

![Screenshot (202)](https://github.com/user-attachments/assets/b2ed7b82-9818-4cc5-9856-c19a987a975b)


### RESULT
Thus,the program to Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError was implemented and executed successfully.
