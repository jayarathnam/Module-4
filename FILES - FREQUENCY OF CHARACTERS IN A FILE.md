# Exp.No:4d
## FILES - FREQUENCY OF CHARACTERS IN A FILE

---

### AIM  
To write a Python program that reads a file and counts the frequency of each character in it.

---

### ALGORITHM

1. Begin the program.  
2. Define the function `create_file()` that accepts two arguments:  
   - `file_path`: The path to the file.  
   - `content`: The string content to be written into the file.  
3. Open the file specified by `file_path` in write mode (`'w'`), and write the provided `content` into the file.  
4. Close the file (this is automatically done when exiting the `with` block).  
5. Define the function `character_frequency()` that accepts one argument:  
   - `file_path`: The path to the file whose character frequency is to be calculated.  
6. Open the file specified by `file_path` in read mode (`'r'`), and read its content into the variable `content`.  
7. Initialize an empty dictionary (`d1`) to store the frequency of each character using `defaultdict(int)`.  
8. Loop through each character in the `content`:  
   - For each character `ch`, increment its corresponding frequency in the dictionary `d1`.  
9. Return the dictionary `d1`, which contains the frequency of each character in the file.  
10. Terminate the program.

---

### PROGRAM

```

def create_file(file_path, file_content):
    with open(file_path,"w") as file:
        file.write(file_content)

def count_words_in_file(file_path):
    with open(file_path,"r") as file:
        text=file.read()
        words=text.split()
        return len(words)


```


### OUTPUT

<img width="1111" height="348" alt="image" src="https://github.com/user-attachments/assets/a72d1f7e-19d9-44fc-8316-55ea77ac96c0" />

### RESULT
Thus the Python program to read a file and count the number of words in it was successfully created.
