# Exp.No:4c
## EXCEPTION HANDLING

---

### AIM  
write a python program for the solution of value error in exception handling and check whether the number is even or odd.

---

### ALGORITHM

1.Prompt User: Ask the user to input a number.

2.Try Block:

Convert the input to an integer using int().

Use % 2 to check if the number is even or odd.

3.Except Block:

If conversion fails (e.g., input is "abc"), catch the ValueError and display an error message.

4.Output:

Print whether the number is even or odd, or show an error message for invalid input.


---

### PROGRAM

```
def digit():
    try:
        a=int(input())
        if(a%2==0):
            print("You entered even number")
        else:
            print("An odd number")
    except:
        print("Enter only number")
digit()
```

### OUTPUT

![Screenshot (201)](https://github.com/user-attachments/assets/583aa39a-0f41-4e54-b3fb-27b6807851e2)


### RESULT
Thus,the program for the solution of value error in exception handling and check whether the number is even or odd was implemented and executed successfully.
